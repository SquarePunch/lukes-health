# Health Tracking Repository

This repository is designed to keep records of health metrics, including nutrition, exercise, medication, and psychological well-being. The ultimate goal is to improve life quality for both body and mind, storing valuable insights so that future actions or lifestyle changes can be easily adopted (inherited).

## Proposed Markdown File Structure

To efficiently manage and retrieve information, primarily using Markdown (`.md`) files, the following directory structure is proposed:

```text
.
├── profiles/
│   ├── psychological_profile.md  # Core mental health baseline, personality traits, triggers, coping mechanisms, and mental goals.
│   ├── nutrition_profile.md      # Dietary preferences, restrictions, target macros, allergies, and standard meal plans.
│   └── medical_profile.md        # Baseline physical health, current conditions, historical data, and biometrics.
├── daily_logs/
│   └── YYYY/                     # Grouped by year
│       └── YYYY-MM-DD.md         # Daily logs for capturing daily nutrition, exercise, medication, and subjective feelings.
├── insights/
│   ├── experiments.md            # Active and past lifestyle experiments (e.g., new diet, different sleep schedule) and their outcomes.
│   └── inherited_knowledge.md    # Distilled, long-term lessons and rules that have proven effective over time.
└── resources/
    ├── workout_routines.md       # Standardized exercise regimens and workout plans.
    └── medication_history.md     # Comprehensive history of medications, dosages, and observed side effects.
```

## Daily Log Template (`daily_logs/YYYY/YYYY-MM-DD.md`)

A consistent daily template ensures data is comparable over time.

```markdown
# Date: YYYY-MM-DD

## 🍎 Nutrition
- **Breakfast:**
- **Lunch:**
- **Dinner:**
- **Snacks:**
- **Water Intake:**

## 🏋️ Exercise
- **Activity:**
- **Duration:**
- **Intensity / Notes:**

## 💊 Medication & Supplements
- **Morning:**
- **Evening:**
- **As Needed:**

## 🧠 Mind & Feelings
- **Overall Mood:** (e.g., 1-10 scale)
- **Energy Levels:**
- **Stress / Anxiety:**
- **Substance Cravings / Withdrawal Symptoms:**
- **Days Sober:**
- **Subjective Notes (How I feel):**

## 📝 Other / General Notes
- Sleep quality, social interactions, or any other relevant events.
```

## Workflow & Guidelines

1. **Daily Tracking:** Create a new file in `daily_logs/` for each day using the provided template. Keep entries brief but accurate.
2. **Periodic Reviews:** At the end of each week or month, review your daily logs to identify trends (e.g., how a specific food affects your mood or energy).
3. **Updating Profiles:** Your profiles (`psychological_profile.md`, `nutrition_profile.md`) are living documents. Update them as your baseline shifts or as you learn more about yourself.
4. **Distilling Insights:** When you discover a strong correlation (e.g., "Medication X always makes me sleepy" or "Running in the morning improves my mood all day"), document it in `insights/inherited_knowledge.md`. This ensures that your future self can inherit these lessons easily without having to relearn them.
