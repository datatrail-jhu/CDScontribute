---
title: CDS Content Development Workflow
output:
  pdf_document: default
  html_document: default
---

### For each course:
- Create a separate GitHub repository @ https://github.com/datatrail-jhu/ (format: "cds_coursename")
- within each course you'll create two directories: 'manuscript' and 'scripts'
- within 'manuscript', create a 'resources' directory. Within resources, create 'images'


### Steps for each lesson:

1. **Course material with images**: 
- save here: manuscript/00_lecturename.md
- Course Name should be at top as an H1 (#)
- All other headers should be H3 (###)
- images in .md file should be referred to  with the following path: "images/00_coursename/00_coursename_lecturename-01.png"
- Quiz at bottom

2. **Google slides**:
- make a copy from starting slides [here](https://docs.google.com/presentation/d/143gvqcynq_bl7iVd2G9yjumwJJkAy0S6CyNCsrJ2LgE/edit#slide=id.p)
- Title using following convention: 00_coursename_lecturename
- update slide link at bottom of manuscript/00_lecturename.md (created in step 1)
- After slides are complete, save a pdf of slides to:  
manuscript/resources/images/00_coursename/00_coursename_lecturename.pdf
- use [pdf2png](pdf2png.com) to convert that pdf to individual pngs ; save this in same path as above (manuscript/resources/images/00_coursename/00_coursename_lecturename-00.png) ; these are what you will refer to in step 1

3. **Script file**: 
- 1 paragraph per slide
- saved in scripts directory
- use _script.md at end of filename (ie scripts/00_lecturename_script.md)

4. **Compile Ari video**:
- details to follow on this
- Add Ari video link updated in Course material .md





