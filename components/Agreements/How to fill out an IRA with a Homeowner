<template>
  <div class="lesson-container">
    <!-- Header with Logo -->
    <header class="lesson-header">
      <div class="logo-mark">
        <svg viewBox="0 0 40 40" class="house-icon">
          <path d="M20 4L4 18h5v14h22V18h5L20 4zm-6 26V22h12v8H14z" fill="currentColor"/>
        </svg>
      </div>
      <h1 class="lesson-title">How to Fill Out an IRA with a Homeowner</h1>
    </header>

    <!-- Video Section -->
    <section class="video-section">
      <div class="video-wrapper">
        <iframe
          src="https://www.youtube.com/embed/KeiSbmSu6QI"
          title="How to fill out an IRA with a Homeowner"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </section>

    <!-- The Big Picture -->
    <section class="content-section">
      <h2 class="section-heading">The Big Picture</h2>
      <div class="card-grid">
        <div class="info-card">
          <div class="card-icon what-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <circle cx="12" cy="12" r="10"/>
              <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/>
              <line x1="12" y1="17" x2="12.01" y2="17"/>
            </svg>
          </div>
          <h3 class="card-title">What It Is</h3>
          <p class="card-text">
            The IRA (Insurance Restoration Agreement) is a legal document that authorizes your company to represent the homeowner in working with their insurance company to repair damage from a storm or event. It outlines the homeowner's agreement to proceed with the restoration project pending insurance approval.
          </p>
        </div>

        <div class="info-card">
          <div class="card-icon why-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
            </svg>
          </div>
          <h3 class="card-title">Why It Matters</h3>
          <p class="card-text">
            Filling this out correctly is critical to the entire sales process. It allows the job to move forward legally, ensures insurance correspondence flows smoothly, and protects both you and the homeowner. Mistakes or missing details can lead to delays of weeks, poor customer experience, or lost deals.
          </p>
        </div>

        <div class="info-card">
          <div class="card-icon how-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/>
            </svg>
          </div>
          <h3 class="card-title">How It Fits</h3>
          <p class="card-text">
            This step happens right after the homeowner decides to file a claim, ideally while they're on the phone with their insurance company. It falls within the "In-Home / Pitch" stage, after initial interest has been confirmed and right before starting work on the property.
          </p>
        </div>
      </div>
    </section>

    <!-- Watch Out -->
    <section class="content-section warning-section">
      <h2 class="section-heading">Watch Out</h2>
      <p class="section-subtext">Common mistakes that cost deals and cause delays:</p>
      <ul class="warning-list">
        <li class="warning-item">
          <span class="warning-icon">✕</span>
          <span>Skipping the claim number</span>
        </li>
        <li class="warning-item">
          <span class="warning-icon">✕</span>
          <span>Not asking about code coverage</span>
        </li>
        <li class="warning-item">
          <span class="warning-icon">✕</span>
          <span>Signing before the rep fully understands the IRA</span>
        </li>
        <li class="warning-item">
          <span class="warning-icon">✕</span>
          <span>Filling it out before a claim has been filed (in most cases, it's smoother to do during/after)</span>
        </li>
      </ul>
    </section>

    <!-- Your Toolkit -->
    <section class="content-section">
      <h2 class="section-heading">Your Toolkit</h2>
      <p class="section-subtext">Have these ready before you start:</p>
      <ul class="toolkit-list">
        <li class="toolkit-item">
          <span class="check-icon">✓</span>
          <span>IRA (printed or digital copy)</span>
        </li>
        <li class="toolkit-item">
          <span class="check-icon">✓</span>
          <span>Pen or tablet</span>
        </li>
        <li class="toolkit-item">
          <span class="check-icon">✓</span>
          <span>SalesRabbit access for storm dates</span>
        </li>
        <li class="toolkit-item">
          <span class="check-icon">✓</span>
          <span>Homeowner's insurance info</span>
        </li>
      </ul>
    </section>

    <!-- Practice It -->
    <section class="content-section">
      <h2 class="section-heading">Practice It</h2>
      <div class="practice-grid">
        <div class="practice-card solo">
          <div class="practice-header">
            <span class="practice-emoji">👤</span>
            <h3 class="practice-title">Solo Practice</h3>
          </div>
          <ol class="practice-list">
            <li>Read the IRA aloud, line by line, to yourself until you're confident explaining every part.</li>
            <li>Write out the top 5 most important things to remember when filling it out.</li>
          </ol>
        </div>

        <div class="practice-card peer">
          <div class="practice-header">
            <span class="practice-emoji">👥</span>
            <h3 class="practice-title">Peer Practice</h3>
          </div>
          <ol class="practice-list">
            <li>Roleplay with another rep: one is the homeowner, the other practices walking through the IRA.</li>
          </ol>
        </div>
      </div>
    </section>

    <!-- Completion Button -->
    <section class="completion-section">
      <button 
        class="completion-button" 
        @click="markComplete"
        :disabled="isCompleted"
      >
        <span v-if="!isCompleted">I've Reviewed This Lesson</span>
        <span v-else>✓ Completed</span>
      </button>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IraLessonComponent',

  props: {
    ctx: {
      type: Object,
      required: true
    }
  },

  data() {
    return {
      isCompleted: false
    };
  },

  computed: {
    learnerName() {
      return this.ctx?.learner?.first_name || 'there';
    }
  },

  methods: {
    markComplete() {
      if (this.isCompleted) return;
      this.isCompleted = true;
      this.$emit('completed');
    }
  }
};
</script>

<style scoped>
/* CSS Variables for HAVN Brand */
:root {
  --havn-orange: #F5A623;
  --havn-orange-dark: #E8940F;
  --havn-purple: #5B2D86;
  --havn-purple-light: #7B4BA6;
}

/* Base Container */
.lesson-container {
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

.section-heading {
  font-size: 1.35rem;
  font-weight: 700;
  color: #5B2D86;
  margin: 0 0 8px 0;
  padding-bottom: 8px;
  border-bottom: 3px solid #F5A623;
  display: inline-block;
}

.section-subtext {
  color: #666;
  margin: 0 0 16px 0;
  font-size: 0.95rem;
}

/* Info Cards Grid */
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 20px;
}

.info-card {
  background: #fff;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  border-top: 4px solid #F5A623;
}

.card-icon {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 12px;
}

.card-icon svg {
  width: 22px;
  height: 22px;
}

.what-icon {
  background: rgba(245, 166, 35, 0.15);
  color: #F5A623;
}

.why-icon {
  background: rgba(91, 45, 134, 0.1);
  color: #5B2D86;
}

.how-icon {
  background: rgba(245, 166, 35, 0.15);
  color: #E8940F;
}

.card-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #5B2D86;
  margin: 0 0 8px 0;
}

.card-text {
  font-size: 0.95rem;
  color: #555;
  margin: 0;
}

/* Warning Section */
.warning-section {
  background: linear-gradient(135deg, #fff5f5 0%, #fff 100%);
  padding: 24px;
  border-radius: 12px;
  border-left: 4px solid #e53935;
}

.warning-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.warning-item {
  display: flex;
  align-items: flex-start;
  gap: 12px;
  padding: 12px 0;
  border-bottom: 1px solid rgba(0, 0, 0, 0.06);
}

.warning-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.warning-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  height: 24px;
  background: #e53935;
  color: #fff;
  border-radius: 50%;
  font-size: 12px;
  font-weight: bold;
  flex-shrink: 0;
}

/* Toolkit Section */
.toolkit-list {
  list-style: none;
  padding: 0;
  margin: 0;
  background: #fff;
  border-radius: 12px;
  padding: 16px 24px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
}

.toolkit-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 12px 0;
  border-bottom: 1px solid rgba(0, 0, 0, 0.06);
}

.toolkit-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.check-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 24px;
  height: 24px;
  background: #F5A623;
  color: #fff;
  border-radius: 50%;
  font-size: 14px;
  font-weight: bold;
  flex-shrink: 0;
}

/* Practice Section */
.practice-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}

.practice-card {
  background: #fff;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
}

.practice-card.solo {
  border-top: 4px solid #F5A623;
}

.practice-card.peer {
  border-top: 4px solid #5B2D86;
}

.practice-header {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 16px;
}

.practice-emoji {
  font-size: 1.5rem;
}

.practice-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #5B2D86;
  margin: 0;
}

.practice-list {
  margin: 0;
  padding-left: 20px;
  color: #555;
}

.practice-list li {
  margin-bottom: 12px;
}

.practice-list li:last-child {
  margin-bottom: 0;
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

.completion-button:disabled {
  background: linear-gradient(135deg, #F5A623 0%, #E8940F 100%);
  cursor: default;
  box-shadow: 0 4px 15px rgba(245, 166, 35, 0.3);
}

/* Mobile Responsive */
@media (max-width: 600px) {
  .lesson-container {
    padding: 16px;
  }

  .lesson-title {
    font-size: 1.4rem;
  }

  .section-heading {
    font-size: 1.2rem;
  }

  .card-grid,
  .practice-grid {
    grid-template-columns: 1fr;
  }

  .info-card,
  .practice-card {
    padding: 20px;
  }

  .completion-button {
    width: 100%;
    padding: 16px 24px;
  }
}
</style>
