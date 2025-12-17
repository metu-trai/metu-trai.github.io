<!-- Graduate Course on Trustworthy and Responsible AI (CENG7880 - METU Dept. of Computer Eng.)-->

<style>
.aS {
  display: block;
  list-style-type: disc;
  margin-left: 15px;
  margin-right: 15px;
  float: left;
  
}

.divS{
  display: block;
  list-style-type: disc;
  overflow: auto;
  padding-left: 60px;
  padding-right: 60px;
  margin:auto;
}

/* By Dominik Biedebach @domobch */

/* NAVIGATION */
nav {
  width: 100%;
  margin: 0 auto;
  padding: auto;
}

/* By Dominik Biedebach @domobch */
nav ul {
  list-style: none;
  text-align: center;
}
nav ul li {
  display: inline-block;
}
nav ul li a {
  display: block;
  padding: 1px;
  text-decoration: none;
  color: #5d5d5d;
  font-weight: 800;
  text-transform: uppercase;
  margin: 1px 1px;
  margin-top: 15px;
}
nav ul li a,
nav ul li a:after,
nav ul li a:before {
  transition: all .5s;
}
nav ul li a:hover {
  color: #555;
}

/* By Dominik Biedebach @domobch */


/* stroke */
nav.stroke ul li a,
nav.fill ul li a {
  position: relative;
}
nav.stroke ul li a:after,
nav.fill ul li a:after {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  width: 0%;
  content: '.';
  color: transparent;
  background: #333;
  height: 1px;
}
nav.stroke ul li a:hover:after {
  width: 100%;
}

nav.fill ul li a {
  transition: all 2s;
}


}
</style>


  <nav class="stroke">
    <ul>
      <li><a class="aS" href="#about">About the Course</a></li>
      <li><a class="aS" href="#instructor">Instructor</a></li>
      <li><a class="aS" href="#announcements">Announcements</a></li>
      <li><a class="aS" href="#weeklycoverage">Weekly Coverage</a></li>
    </ul>
  </nav>


------

### <tag id="about">About the Course</tag>

Deep learning based methods and their uses in various AI applications are very rapidly transforming science and technology. Although there is a tremendous interest in such methods in various fields such as computer vision, pattern recognition, speech recognition, natural language processing, robotics etc., the computational mechanisms for trust and responsibility in AI are still unsolved problems. This course provides an opportunity to students to raise awareness about the social, ethical and policy implications of AI; to study and develop deep learning based methods that are robust, explainable and fair.

This is a graduate-level course taught (<a href="https://catalog.metu.edu.tr/course.php?prog=571&course_code=5717880">CENG7880</a>) at the <a href="https://ceng.metu.edu.tr">Dept. of Computer Engineering</a>, <a href="https://metu.edu.tr">METU</a>. 

#### Catalog Description

Ethical concepts and principles of trust and responsibility in AI; computational methods for dependability and robustness in AI; computational methods for explainability in AI; computational methods for bias and fairness in AI.

#### Background Requirements

* Background in deep learning: The students must have taken <a href="https://catalog.metu.edu.tr/course.php?prog=571&course_code=5710403">CENG403 (Introduction to Deep Learning)</a> or <a href="https://catalog.metu.edu.tr/course.php?prog=571&course_code=5710501">CENG501 (Deep Learning)</a>.
* Programming skills in Python.

### <tag id="instructor">Instructor</tag> 

Prof. Dr. Sinan Kalkan<br>
<a href="https://metu.edu.tr">METU</a> <a href="https://ceng.metu.edu.tr">Dept. of Computer Engineering</a> and <a href="https://romer.metu.edu.tr">METU Robotics and AI Center</a><br>
<a href="https://user.ceng.metu.edu.tr/~skalkan/">https://user.ceng.metu.edu.tr/~skalkan/</a>

### <tag id=announcements>Announcements</tag> 

* Please fill the following form for submitting your selected papers (D: 16 October): <a href="https://forms.gle/A3taWgxoCHumfYfz9">https://forms.gle/A3taWgxoCHumfYfz9</a>

### <tag id=weeklycoverage>Weekly Coverage</tag> 

| Week  | Topics | Material | 
| ------------- | ------------- |  ------------- |
| Week 1 (1 Oct)  | Introduction to the course and the main concepts in trustworthy and responsible AI  | <a href="./slides/CENG7880_week1.pdf">slides</a> |
| Week 2 (8 Oct)  | ML/DL Fundamentals  | <a href="./slides/CENG7880_week2.pdf">lecture notes</a> |
| Week 3 (15 Oct)  | ML/DL Recent Trends  | <a href="./slides/CENG7880_week3.pdf">slides</a> |
| Week 4 (22 Oct)  | Robust AI: Robustness to Distribution Shifts; Label Shifts & Using Importance Weights  | <a href="./slides/CENG7880_week4.pdf">slides</a> and <a href="https://colab.research.google.com/drive/1fpxfcIJW5UxxX72fsS98a0fkXSEeTRGr?usp=drive_link">Colab Tutorial on Label Shift</a> (by Ugur Yalcin)|
| Week 5 (29 Oct)  | No lectures owing to the Republic Day of Turkey  | |
| Week 6 (5 Nov)  | Robust AI: Robustness to Covariate Shifts with Importance Weights; Detecting Covariate Shifts; Adversarial Robustness | <a href="./slides/CENG7880_week6.pdf">slides</a> and <a href="https://colab.research.google.com/drive/1fpxfcIJW5UxxX72fsS98a0fkXSEeTRGr?usp=drive_link">Colab Tutorial on Covariate Shift</a> (by Ugur Yalcin) |
| Week 7 (12 Nov)  | Robust AI: Adversarial Robustness; Adversarial Sample Generation; Adversarial Training; Randomized Smoothing; Certified Robustness; Jailbreaking LLMs | <a href="./slides/CENG7880_week7.pdf">slides</a> |
| Week 8 (19 Nov)  | Robust AI: Calibration, Conformal Prediction, Uncertainty Types | <a href="./slides/CENG7880_week8.pdf">slides</a> |
| Week 9 (26 Nov)  | Robust AI: Uncertainty Quantification; Explainable AI: Feature Attribution Methods, LIME, SHAP, Gradient-based Saliency Methods | <a href="./slides/CENG7880_week9.pdf">slides</a> |
| Week 10 (3 Dec)  | Explainable AI: Quality of feature attribution methods; Counterfactual Explanations  | <a href="./slides/CENG7880_week10.pdf">slides</a> |
| Week 10 (3 Dec)  | Explainable AI: Guest lecture on Concept Bottleneck Models (CBMs) by <a href="https://user.ceng.metu.edu.tr/~emre/">Dr Emre Akbas</a>.  | <a href="./slides/CENG7880_week10_CBMs.pdf">slides</a> |
| Week 11 (10 Dec)  | Explainable AI: Representation Attribution (Concept Activation Vector); Data Attribution; Explainability in LLMs.  | <a href="./slides/CENG7880_week11.pdf">slides</a> |
| Week 12 (17 Dec)  | Fairness: Sources of bias; Fairness notions, principles, definitions, criteria, and measures. | <a href="./slides/CENG7880_week12.pdf">slides</a> |

