- from pptx import Presentation

# Create a presentation object
ppt = Presentation()

# Add title slide
slide = ppt.slides.add_slide(ppt.slide_layouts[0])
title = slide.shapes.title
subtitle = slide.placeholders[1]

title.text = "Statistical Testing Overview"
subtitle.text = "Paired t-test, ANOVA, Z, t, F, and Chi-square Tests"

# Add slide for Paired t-test
slide = ppt.slides.add_slide(ppt.slide_layouts[1])
title = slide.shapes.title
content = slide.shapes.placeholders[1]

title.text = "Paired Sample t-test"
content.text = """
- Compares two related means (before and after).
- Null Hypothesis (H0): Mean difference is zero.
- Alternative Hypothesis (H1): Mean difference is not zero.
- Test statistic: t = (mean_diff) / (std_dev_diff / sqrt(n)).
- Compare t-statistic to critical t-value or p-value to alpha.
"""

# Add slide for ANOVA
slide = ppt.slides.add_slide(ppt.slide_layouts[1])
title = slide.shapes.title
content = slide.shapes.placeholders[1]

title.text = "ANOVA (Analysis of Variance)"
content.text = """
- Compares means of 3 or more groups.
- Null Hypothesis (H0): All group means are equal.
- Alternative Hypothesis (H1): At least one group mean is different.
- Test statistic: F = (between-group variance) / (within-group variance).
- Decision: Compare F-statistic to critical F-value or p-value to alpha.
"""

# Add slide for Decision Making
slide = ppt.slides.add_slide(ppt.slide_layouts[1])
title = slide.shapes.title
content = slide.shapes.placeholders[1]

title.text = "Decision Making: p-value vs Critical Value"
content.text = """
- Compare p-value to alpha:
  - If p-value < alpha, reject H0.
  - If p-value >= alpha, fail to reject H0.
- Compare test statistic to critical value:
  - If calculated stat > critical value, reject H0.
"""

# Add slide for Finding Critical Values
slide = ppt.slides.add_slide(ppt.slide_layouts[1])
title = slide.shapes.title
content = slide.shapes.placeholders[1]

title.text = "Finding Critical Values"
content.text = """
- Use Z, t, F distribution tables or software.
- Software
👋 Hi, I’m @jharr2367
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jharr2367/jharr2367 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
