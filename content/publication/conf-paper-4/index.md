---
title: 'Attendance Tracking with Face Recognition Through Hidden Markov Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sneha Balasubramoni

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-03-16T00:00:00Z'
doi: '10.1109/ICEARS53579.2022.9751888'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '2022 International Conference on Electronics and Renewable Systems (ICEARS)'

abstract: Facial recognition is one of the most secure ways to identify a person. Manual attendance in organizations, be it in classrooms or libraries or even attendance for teachers is truly a hassle. Due to the inception of Hidden Markov Model (HMM), they have worked well with image data and it has plethora of facial recognition applications. In this paper, yet another application of face recognition with HMM is explored, where it is integrated with Singular Value Decomposition (SVD) and track the attendance of the students present in a database. HMMs deal with data in the form of states and sequences. Face recognition looked through the lens of HMMs which can be framed in the following manner: a face is split into regions vertically (forehead, chin, etc.) and a particular sequence is always preserved. A rectangular window of fixed size is passed over every test image, and for every vector obtained, the probability of data is calculated. For training, probability computation is done with the help of the Baum Welch algorithm. This whole model is connected to a simple program to keep track of the students leaving and entering the classroom, marking their presence only and updating the same information in the college’s database.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Facial Recognition
  - Attendance Tracking
  - Hidden Markov Model
  - Singular Value Decomposition

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/Sneha421/Attendance-Tracker-using-HMM'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---

{{% callout note %}} Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.{{% /callout %}}
