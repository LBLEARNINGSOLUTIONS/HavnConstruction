<template>
  <div class="ira-lesson">
    <!-- Header -->
    <div class="lesson-header">
      <div class="logo-mark">
        <svg viewBox="0 0 40 40" class="house-icon">
          <path d="M20 4L4 18h5v14h22V18h5L20 4zm-6 26V22h12v8H14z" fill="currentColor"/>
        </svg>
      </div>
      <h1 class="lesson-title">Professionalism</h1>
    </div>

    <!-- Video Section -->
    <div class="video-section">
      <div class="video-wrapper">
        <iframe
          src="https://www.youtube.com/embed/MSTKcqFjpsY"
          title="Professionalism"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <!-- Description -->
    <div class="content-section">
      <div class="description-card">
        <p class="description-text">
          How to dress and conduct yourself in a professional manner while working at HAVN Construction.
        </p>
      </div>
    </div>

    <!-- Completion Button -->
    <div class="completion-section">
      <button 
        class="completion-button" 
        :class="{ completed: isCompleted }"
        @click="complete"
        :disabled="isCompleted"
      >
        <span v-if="!isCompleted">I've Reviewed This Lesson</span>
        <span v-else>✓ Completed</span>
      </button>
    </div>
  </div>
</template>

<style scoped>
.ira-lesson {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  color: #333;
  line-height: 1.6;
}

/* Header */
.lesson-header {
  text-align: center;
  margin-bottom: 32px;
}

.logo-mark {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 48px;
  height: 48px;
  color: #F5A623;
  margin-bottom: 12px;
}

.house-icon {
  width: 100%;
  height: 100%;
}

.lesson-title {
  font-size: 1.75rem;
  font-weight: 700;
  color: #5B2D86;
  margin: 0;
}

/* Video Section */
.video-section {
  margin-bottom: 40px;
}

.video-wrapper {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(91, 45, 134, 0.15);
}

.video-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

/* Section Styles */
.content-section {
  margin-bottom: 40px;
}

/* Description Card */
.description-card {
  background: #fff;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  border-left: 4px solid #5B2D86;
}

.description-text {
  font-size: 1.1rem;
  color: #444;
  margin: 0;
  line-height: 1.6;
}

/* Completion Section */
.completion-section {
  text-align: center;
  padding: 32px 0 16px;
}

.completion-button {
  background: linear-gradient(135deg, #5B2D86 0%, #7B4BA6 100%);
  color: #fff;
  border: none;
  padding: 16px 48px;
  font-size: 1.1rem;
  font-weight: 600;
  border-radius: 50px;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(91, 45, 134, 0.3);
}

.completion-button:hover:not(:disabled) {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(91, 45, 134, 0.4);
}

.completion-button:active:not(:disabled) {
  transform: translateY(0);
}

.completion-button.completed {
  background: linear-gradient(135deg, #F5A623 0%, #E8940F 100%);
  cursor: default;
  box-shadow: 0 4px 15px rgba(245, 166, 35, 0.3);
}

/* Mobile Responsive */
@media (max-width: 600px) {
  .ira-lesson {
    padding: 16px;
  }

  .lesson-title {
    font-size: 1.4rem;
  }

  .description-card {
    padding: 20px;
  }

  .completion-button {
    width: 100%;
    padding: 16px 24px;
  }
}
</style>

<script lang='es6'>
module.exports = {
  name: 'ProfessionalismLesson',

  props: ['ctx', 'ui', 'api'],

  data() {
    return {
      isCompleted: false
    };
  },

  beforeMount() {
    this.$options.components = this.ui;
  },

  computed: {
    learner() {
      return this.ctx?.learner || {};
    },
    learnerName() {
      return this.learner.first_name || 'there';
    }
  },

  methods: {
    complete() {
      if (this.isCompleted) return;
      this.isCompleted = true;
      this.$emit('completed');
    }
  },

  mounted() {
    this.$emit('loaded');
  }
};
</script>
