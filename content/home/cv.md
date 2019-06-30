+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Curriculum Vitae"
subtitle = ""
widget = "CV"

# CV location
cv_pdf = "http://www.lps.ens.fr/~krzakala/cv_krzakala.pdf"

# group logo location
group_logo = "http://vignette4.wikia.nocookie.net/eberron/images/7/7c/114862_CN_GL.jpg/revision/latest?cb=20111007220917"
group_name = "Sphinx TEAM"

# Order that this section will appear in.
weight = 3

# List your academic interests.
[interests]
  interests = [
    "Statistical Physics",
    "Machine learning",
    "Random Optimization Problems",
    "Inference on graphs",
    "Information theory",
    "Computational optics"
  ]

# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "Postdoc"
  institution = "Roma, La Sapienza"
  year = 2004
  
[[education.courses]]
  course = "PhD in Statistical Physics"
  institution = "Orsay, Paris XI"
  year = 2002

[[education.courses]]
  course = "MSc in Physics"
  institution = "Orsay, Paris XI"
  year = 1999

# List your honors
[[honor.fellowships]]
  name = "Member of the Insitut Universitaire de France"
  years = "2015 - ..."

[[honor.fellowships]]
    name = "Holder of the chair CFM-ENS on datascience"
    years = "2016 - ..."

+++