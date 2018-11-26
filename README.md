# Fast Image Deblurring using low rank approximation

> **Guidelines for the group project**
> CSE/ECE 478, Monsoon 2018
> https://link.springer.com/content/pdf/10.1007%2Fs11554-015-0539-x.pdf

## STEP-1: Submit Project Preference

- [List of suggested projects.](https://docs.google.com/document/d/1PZ0Dx9Yl9kTkXzGNFO2rFA2NRANA2okk7Pf5Fpo4lPo/edit)

- Assign a single project coordinator among your team and have him/her fill the following form. NOTE: Enter only project IDs for preferences and not project titles: https://goo.gl/forms/InjqbujrtZFsPLDM2

- _NOTE: Ensure that there is a single form submission for the project. E.g. If a project has 3 team members, ensure ONLY ONE of the project members submits the form --  do NOT submit the form 3 times ! Failure to do so will delay the announcement of final project listing._

- In case you intend to do a project NOT listed above, you’ll still need to fill the form, with  preferences. That way, if your proposed project is not deemed viable, you’ll have a backup. In this case, make sure you fill in the title of your proposed project.

- Project assignment to teams will be done on a first-come-first-served basis (i.e. if two teams have same first preference, tie-breaking will be on the basis of submission timestamp). In the unlikely case timestamps are same, tie-breaking will be random choice. In case preferences are all taken up (due to above criteria), a project will be randomly assigned from list of projects not selected by any group.

- If you have any questions about a project and its scope, you can discuss with TAs / instructors.

- Under no circumstances, the projects/preferences can be changed once submitted. Discuss with your team-mates and think carefully before you submit the form.

- Project List up : 20 September, 5.30 PM
- Deadline for submitting the form:  23 September, 11.59 PM
- Final project list announcement:   25 September (Tuesday), 5.30 PM

## STEP-2: Submit Project Proposal (DONE)

Once project is finalized, a project proposal needs to be submitted. The project proposal must include the following items -- use images whenever possible:

- Project Id and title
- Github link (see instructions for this in the next step)
- Team Members
- Main goal(s) of the project
- Problem definition (What is the problem? How things will be done ?)
- Results of the project (What will be done? What is the expected final result ?)
- Team members and tasks for each member (What will each team member do?)
- What are the project milestones and expected timeline ?

- Deadline for submitting project proposal: 29 September, 11.59 PM

- _NOTE: Based on contents of the proposal, your project plan may need to be modified. We will contact your team coordinator._

## STEP-4: Manage your Project

- The code for the project will need to be uploaded to github. Create a project and add yourselves as individual contributors to the projects. IMPORTANT: Add github repository link to project proposal.
- To avoid running into github’s size limits, ensure you upload only code and other documents (project proposal, final report) and NOT data (images).
- Periodically backup/update your code on github -- we will be checking for updates.

## STEP-5: Project Progress Review

- TAs will review the progress of your project. Tentative date: November 10
- Details will be announced.

## STEP-6: Submission and Final Presentation

**You will have 3 deliverables.**

### DELIVERABLE-1: Project Presentation (20 minutes)

- Powerpoint + demo (where appropriate)
- Leave at least 5 minutes for questions from the audience.
- TAs/Instructors may ask detailed questions, so everyone in the team should be familiar with the complete project, not just the part they worked on !

### DELIVERABLE-2:  Github repo

- Along with your code, add a README.md markdown file (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) with
instructions on how to run your code and replicate the results.
- Test your code on a machine different from that used during project development. Include any missing dependencies and how to resolve them in the README.
- Link to input images: Package all images used for training/input to your code into a zip file. Upload this zip file and provide a link to this zip file.
- Link to output images: Package all images obtained as output from your code into a zip file. Upload this zip file and provide a link to this zip file.
- Use a sensible format for input and output filenames (e.g. On running code on input-0001.png, output should be output-0001.png). Alternately, you can include a script which loops through all your input images.
- The results you upload must be bit-identical (match exactly) with the results we get when we run the code.
- _NOTE: Do NOT upload the input/output image zip files on your github repo. Upload them elsewhere (Google Drive) and add their links to README_
- Your project presentation should also be present in the github repo -- we will check the timestamp, so make sure you upload the pptx/pdf files within an hour of your presentation.

### DELIVERABLE-3: Final Project Report

-  Less than 30 pages, double space, due exactly 1 day before your presentation, e.g. if your presentation is at 3pm on Nov 28, project report must be submitted by 3pm on Nov 27.

- You will need to submit final project report on moodle. See next item for format and content of project report:
    - Format of Final Report
    - Introduction (Problem statement, Motivation, Overview (Input - Method - Output) diagram wherever appropriate)
    - Approach (es) considered
    - Work Performed (Experiments, software programming, etc.)
    - Results
    - Successes
    - Failure cases
    - Discussion (Analysis of results, including failure cases, Future Directions)
    - Github Link
    - Acknowledge all codes that you obtained elsewhere.

## Scoring Rubric

- Workload, completeness and novelty: 60%
- Presentation: 20%
- Project report clarity: 20%

## Additional Notes

- In any case, if you wish to have some feedback about the triviality or difficulty of your project, please speak to TAs, instructors.
- Your project work may contribute to your thesis/honors project, but the work you submit for this course must be done within the project submission deadline. It should be a separate deliverable. You may need your Honors/primary advisor’s approval for this.
- You may use MATLAB/C/C++/Java/Python + any packages (OpenCV,ITK, etc) for your project. But merely invoking calls to someones else's software is not substance enough. You should have your own non-trivial coding component.
- If software for the research paper you implement is already available, you should use it only for comparison sake.  You will be expected to implement the paper on your own. Please discuss with TAs/instructors if you need any clarifications for your specific case.
- If your project is novel/new and you are planning to extend it towards a conference submission after the course is over,  you must ensure that a significant portion is completed by project submission deadline time.
