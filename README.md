# Latex templates for submitting the NIH F31 grant

The National Institutes of Health (NIH) has several funding mechanisms. If you are a predoctoral student hoping to secure your own funding, you can apply for their F31 grant and technically be your own PI.

 Since [formatting](https://grants.nih.gov/grants/how-to-apply-application-guide/format-and-write/format-attachments.htm#papersizeandmargins) and navigating all the necessary documents for a federal grant can be overwhelming, here are some Latex templates and unsolicited tips to help get you started.
 
 Within each folder is an F31 grant component, where there is a `.tex` file for you to edit for your own grant and a `.pdf` is a dummy example and an outline. Additional comments/tips for the most intense parts of the F31, the specific aims and the research strategy are under the `f31-aims-strategy` folder.
 
### What is an F31?
First, check out the latest description of the [F31](https://grants.nih.gov/grants/guide/pa-files/PA-18-671.html) from NIH , including important dates and eligibility information. Depending on your research area, you can select your top picks from the list of participating institutes that will review and actually fund your project. The number of applicants, number of awards, success rates, and total funding from each institution are [reported yearly](https://report.nih.gov/success_rates/index.aspx). Plan strategically if your project can fall under multiple institutions.

 NIH has a complete guide through the [grant process](https://grants.nih.gov/grants/about_grants.htm). The technical details of each grant component and requirement are subject to change, but the latest application guide for fellowships is [here](https://grants.nih.gov/grants/how-to-apply-application-guide/forms-d/fellowship-forms-d.pdf), where `Ctrl+F` is your best friend.

The F31 can fund the remaining years of your PhD. However, it is important to note that there can be a big time gap between submitting your grant, getting it scored, and hearing back about whether it has been awarded (aka a start date for the funds).

### Grant timeline
There are 3 [application cycles](https://grants.nih.gov/grants/how-to-apply-application-guide/due-dates-and-submission-policies/due-dates.htm) in a year. The F31 is always due either April 8, August 8, or December 8 . The general grant process includes:
+ **Get a sponsor**

  This is usually your advisor, who **must** have a funded R01 in a similar area as your grant. If not, you gotta find a close collaborator to be your sponsor, and then use your advisor as the co-sponsor.

+ **Get 3 recommendations**

  You need Reference Letters, and *they* are the ones who submit these online. You also should try to get letters of support if there are gaps in your application.

+ **Write and rewrite**

  Here are the [main documents](https://grants.nih.gov/grants/how-to-apply-application-guide/format-and-write/page-limits.htm) you'll have to write. NIH expects that you have the support system to have someone to guide you through the specific aims, research strategy, and etc.

+ **Give it to your university's grants office**

  You will pass it back and forth until they are happy and then *they* will submit it.

+ **Get assigned a study section and date of [review](https://grants.nih.gov/grants/peer-review.htm)**

+ **Get a score** (hopefully)

  The scoring guide is [here](https://grants.nih.gov/grants/peer/guidelines_general/scoring_system_and_procedure.pdf). Review the score, percentile, and feedback by the reviewers with your Program Officer (PO; the person at NIH that is your contact person for information and suggestions for any part of the grant process) and decide whether you should (a) wait for award decisions, (b) start a re-submission, or (c) start another grant proposal altogether.

+ **Get an Advisory Council date**

  Grants are selected for funding.

+ **Wait to get an offer**

FYI, I started planning in the summer of 2016, writing and rewriting in the fall, submitted that December to the National Institute of Cancer, reviewed in February 2017, got scored and decided to resubmit, resubmitted that April, reviewed that June, got scored (impact factor: 21, percentile: 16), decided to wait for awards, council met in September 2017, aaaaand awarded in February 2018. There was a delay for all grants - I think NIH funds were undetermined for 2018 for a while.

The resubmission process is relatively short. I had to address the reviewers' concerns in the research strategy, write the 'Introduction to Resubmission or Revision Application', added a letter of support, and resubmit the entire grant.

## Writing components
Check out the PDF files in each folder to see dummy examples of content in some of the writing components (not all were included since a representative template can be reused).

The order of what to write is based on importance:
1. **Specific Aims**

   You need to know *exactly* what the research goals are in words understandable by another researcher in, around, or out of your research domain.
2. **Research Strategy**

   Your project proposal of what you will be doing with the funds. Finishing 2 means you're like, 90% done.

3. **Applicant's Background and Goals for Fellowship Training** - all about you

4. **Biographical Sketch** - your biosketch (NIH has the [biosketch form](https://grants.nih.gov/grants/forms/biosketch.htm))

5. **Description of Institutional Environment and Commitment to Training**

   Try to use components from previous grant applications submitted by your lab. Do include your training program, your university details, on-campus resource, external resources like Amazon Web Services, lab space, equipment, and etc.

5. **everything else**

   This includes a cover letter, grades, and if applicable, protection of human subjects statement.

*Meanwhile*, you should be contacting people to do or get these:
1. **Sponsor and Co-Sponsor Statements** - their background, experience, related projects (e.g., funded grants), and etc.
2. **Letters of Support from Collaborators, Contributors, and Consultants** -- [NIH instructions](and *they* are the ones who submit these online.)
3. **Biographical Sketch** - of sponsors, co-sponsors, and etc.

Note that scoring includes three components:
1. the belief that you as a researcher will succeed in doing the research;
2. your sponsors and collaborators will be helpful in this project; and
3. your research strategy has scientific rigor, serves the institution's goals, and is somewhat unique.

These align with why certain writing components are much lengthy than others.

## Getting started
You're gonna need some stuff first.

### Ubuntu
Tested on 18.04
1. Install Latex, e.g.,

   `sudo apt install texlive-latex-extra`
2. Install an editor, e.g., for TeXstudio:

   ```bash
   sudo add-apt-repository ppa:sunderme/texstudio
   sudo apt-get update
   sudo apt-get install texstudio
   ```
3. Install some open type fonts, specifically for Times New Roman

    `sudo apt-get install msttcorefonts`

4. Open a `.tex` file, e.g., with TeXstudio, edit content, and compile under LuaLaTeX.

### OS X
1. Install Latex, e.g., MacTeX-2018 [instructions](http://www.tug.org/mactex/)
2. Install an editor, e.g., TeXstudio [instructions](https://www.texstudio.org/)
3. Open a `.tex` file, e.g., with TeXstudio, edit content, and compile under LuaLaTeX.
