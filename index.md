METU Dept. of Computer Engineering -- Graduate-level Course CENG7880 -- Trustworthy and Responsible AI

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
      <li><a class="aS" href="#wid">About the Course</a></li>
      <li><a class="aS" href="#summary">Summary</a></li>
      <li><a class="aS" href="#publications">Publications</a></li>
      <li><a class="aS" href="#contact">Contact</a></li>
    </ul>
  </nav>


------

<p align="center">
    <img src="./visuals/dengesizlik_plot.png" width="100%">
    <i>Figure 1: Many problems in practice exhibit strong imbalance towards certain classes or categories, which can severely impact learning performance. (a) Foreground-background imbalance problem in object detection. (b) Imbalance problem among object categories. (Figure source: [Oksuz et al., 2021](https://arxiv.org/abs/1909.00169)).</i>
</p>

-----
### <tag id="wid">What is DENGE?</tag>

DENGE is


### <tag id="summary">Summary</tag> 

Class imbalance 

### <tag id=publications>Publications</tag> 

The list of publicati



### <tag id=contact>Contact</tag> 

Please use the following email address for course related issues: metu-denge [@] googlegroups [dot] com
