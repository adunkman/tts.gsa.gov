---
layout: layouts/jointts/job-updated
permalink: /join/{{ title | slugify }}.html
tags: jobs

################################################################################
#                                                                              #
# INSTRUCTIONS: TTS JOB TEMPLATE                                               #
#                                                                              #
# -----------------------------------------------------------------------------#
# If you are editing this file on GitHub, first make sure you are creating a   #
# new file, and are not editing the template file! To create a new file, go to #
# https://github.com/18F/join.tts.gsa.gov/new/main/positions in your browser.  #
#                                                                              #
# On the new file page, you can paste in the contents of the template file.    #
# Also be sure to type in a filename in the small textbox above the file body  #
# box. You will see the text join.tts.gsa.gov / [ Name your file ...] in main. #
# Type your filename into that box.                                            #
#                                                                              #
# NOTE ABOUT FILENAMES: Your filename should be descriptive about the job      #
# posting that you're creating, and it MUST end with ".md". Don't stress out   #
# about filenames too much, though. They are used for the URL, which can help  #
# people make sure they're on the right page, but most users will probably not #
# notice the URL. Instead, try to make it meaningful to you and others on the  #
# Talent Team so you can find it easily in the future if you need to edit it.  #
#                                                                              #
# For example, if you are posting a job for a content designer, you might      #
# choose names like:                                                           #
#                                                                              #
#    tts-content-designer-2023.md                                              #
#    login-content-designer-2023.md                                            #
#    content-designer-2023.md                                                  #
#    content-designer-june-2023.md                                             #
#                                                                              #
# For the rest of the file, follow the directions as you go, but here are a    #
# couple more tips to help you as you work:                                    #
#                                                                              #
# You are currently inside the portion of the document called "frontmatter."   #
# The frontmatter is the part that starts with just "---" on the first line    #
# and ends with another line that only contains "---" (further down). This     #
# part of the document is not DIRECTLY shown to the user. Instead, this is     #
# where you can set data that will be shown to the user in other parts of the  #
# page, or data that is used to configure how the page is displayed. For       #
# example, the opens and closes dates are set in the frontmatter, but they     #
# will never be shown to the user the way you type them in. Instead, they are  #
# used to determine whether the posting is upcoming, open, or closed, and they #
# will be turned into more human-friendly text when they are displayed.        #
#                                                                              #
# Within this frontmatter block, lines that begin with a hash (#) symbol are   #
# comments. They do not contribute to the web page at all, but they are a nice #
# way of explaining what the data in the frontmatter is. It is okay to delete  #
# these comments when you are done, and it is also okay to leave them if they  #
# might be helpful when editing the page later.                                #
#                                                                              #
# The parts you need to fill out are marked with five red triangles above them #
# like this:                                                                   #
#🔻🔻🔻🔻🔻                                                                   #
#                                                                              #
# After the frontmatter, the rest of the document is in a special version of   #
# Markdown used by the website builder. You will see comments in that section  #
# as well, but they will look like this:                                       #
#                                                                              #
#    {% comment ----------------------------------------------------------- %} #
#    The contents in between these two lines are comments and do not           #
#    contribute to the web page.                                               #
#    {% endcomment -------------------------------------------------------- %} #
#                                                                              #
# It is safe to remove the Markdown comments as well.                          #
#                                                                              #
################################################################################

# This is the position title and the org that is doing the hiring. Please format
# your title as "Org: Position Title" (in quotes!). The organization should be
# a full name rather than an acronym. For example:
#   - U.S. Digital Corps, not USDC
#   - Presidential Innovation Fellows, not PIF
# The exception to this is a TTS role, for which you can just say TTS.
# Role should be just the position title without the org.
#
# NOTE: Be sure to leave the "title: " part at the beginning! These line
# headings are how the site builder knows what the data is. For the rest of the
# frontmatter, please be careful not to delete the headings!
#🔻🔻🔻🔻🔻
title: "Public Experience: Contact Center Analyst"
role: "Contact Center Analyst"

# Put the opening and closing dates of your posting here, if you have them. The
# values you set here will be turned into user-friendly text in other parts of
# this post. Setting it here means you won't have to copy it over and over.
#
# These dates MUST be formatted as YYYY-MM-DD, where month and day are 2-digits.
# If the month number or day of the month are less than 10, add a 0 to the
# front (eg, May would be 05 instead of just 5). This is the only format the
# site builder automatically understands. Anything else will not be understood
# as a date.
#🔻🔻🔻🔻🔻
opens: 2024-09-13
closes: 2024-09-24
# These dates are also used to determine whether a position is upcoming, open,
# or closed. Here's how we decide:
#
# The job is upcoming if:
#   opens is empty OR
#   opens is in the future
#
# The job is open if:
#   opens is in the past OR
#   closes is in the future
#
# The job is closed if:
#   closes is in the past
#
# If either opens or closes is empty, missing, or not a date, the position is
# considered to be upcoming.

# If the position can also close when the maximum number of applications are
# received, include the maximum number of applications here. Remove this line
# or set the value to 0 if the job does not have an application cap.
#🔻🔻🔻🔻🔻
max applications: 0

# Is this a permanent or term appointment? Use either "perm" or "term". This
# will be used to fill in the appointment type on the page with consistent
# language.
#🔻🔻🔻🔻🔻
appointment type: perm

# Put the GS grade this position is being advertised at. For SES positions, set
# the level to 20.
#🔻🔻🔻🔻🔻
gs: 12
# The information you put here will be used to automatically pull salary range
# information.
#
# ⚠️⚠️⚠️ IMPORTANT NOTE: The automatic salary ranges are based on 100% remote
# positions and use the lowest and highest locality areas. If this position is
# not 100% remote, you will need to delete the automatic salary range and input
# it yourself down below. Look for 💰💰💰 to indicate where to do that.
#
# The salary range data is stored in this file:
#
#   _data/pay_ranges.yml
#
# The data file will need to be updated each year to reflect any pay changes.

# List key objectives here. Key objectives and sub-bullets will be displayed in
# the order they are listed here. You do not need to include key objective
# numbers. They will be added automatically.
#
# Each key objective starts on a new line and must start with a dash. It does
# not need to include a number at the beginning. A key objective can be spread
# across multiple lines if you want.
#
# To add sub-bullets to your key objective, add a new line below the key
# objective and indent it with spaces. (The number of spaces does not matter, as
# long as it is more than one). Then, add a dash and your sub-bullet.
# Sub-bullets can also take up multiple lines as long as all of the lines are
# indented the same amount so they line up.
#
# The placeholder information below shows an example of how to format the key
# objectives. This example indents sub-bullets with two spaces:
#🔻🔻🔻🔻🔻
key objectives:
  - Lead Product Delivery
    - Set the vision, strategy, and goals for the Communities and Collaboration Branch.
    - Ensure projects align with TTS priorities and serve the public effectively.
    - Manage multiple complex products and IT projects, anticipating risks and opportunities.
    - Collaborate across TTS and ensure resources are used effectively.
  - Build and Lead Teams
    - Supervise and mentor team members, guiding them on technical and administrative matters.
    - Build teams, assign work, and ensure alignment with branch goals.
    - Foster professional growth and incorporate equity and inclusion in team development.
  - Enhance Product Delivery Expertise
    - Develop and maintain product strategies that align with agency objectives.
    - Collaborate with cross-functional teams to prioritize product requirements.
    - Lead the development process, ensuring timely delivery of features and compliance with standards like the 21st Century IDEA, the M-23-22 "Delivering a Digital-First Public Experience" and other relevant policies.
    - Share best practices and lessons learned to contribute to TTS’s culture of product management.

# If there are any info sessions associated with this position, list them here.
# Each info session needs three pieces of information: the link, the date, and
# the time. See the placeholder below for an example of how to add an info
# session. If the position does not have any info sessions, you can just delete
# the lines that begin with spaces.
#
# IMPORTANT: The date MUST be formatted as YYYY-MM-DD, where the month and day
# are TWO digits. If the month or day is less than 10, add a zero to the front.
# The date is used to sort the info sessions on the page so they are shown
# nearest to furthest. Only info sessions schedule for the future will be shown.
#🔻🔻🔻🔻🔻
info_sessions:

# Put the link applicants need to use to apply for this position here. This link
# will be used for the "Click here to apply" button at the bottom of the
# position page.
#🔻🔻🔻🔻🔻
application link: https://www.usajobs.gov/job/808940800
# This is the end of the frontmatter. After this line is Markdown.
---

{% comment ------------------------------------------------------------------ %}
If you want to include a closed/upcoming/open alert at the top of your page,
leave the following line. The status of the position will be determined by the
opens/closes dates at the top of this document

If you do not want the closed/upcoming/open alert, delete the line below that
says {% include job/status_alert.html %}
🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}

{% comment %}{% include job/status_alert.html %}{% endcomment %}

## Basic information

<!-- markdownlint-disable MD033 -->
Open to U.S. citizens or nationals (residents of American Samoa and Swains Island). Subject to background check. Full information is available on <a href="{{ 'https://www.usajobs.gov/job/808940800' | url }}" class="usa-link">USAJOBS.</a>
<!-- markdownlint-enable MD033 -->

{% comment %}{% include job/full_info_on_usajobs.html %}{% endcomment %}

**Supervisory status:** Non-Supervisory

**Job title:** {{ title }}

{% comment ------------------------------------------------------------------ %}
The job title on USAJOBS is not always the same as the job title as we list it.
To help applicants find the right jobs on USAJOBS, put the title as it appears
on USAJOBS here.
🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}
**Official title in USAJOBS:** Program Analyst

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Number of vacancies:** 1

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Location:** Anywhere in the U.S. (remote)

{% comment ------------------------------------------------------------------ %}
💰💰💰
The salary range for the job can be populated automatically based on the GS grade this posting is advertised at, based on the lowest and highest locality rates.

💰💰💰
If this position is not remote and has geographic restrictions, you can instead specify the salary min and max. For example, if the position is advertised at GS-15 and the position location is only Washington, DC, then (using 2023 pay
rates):

Minimum:  GS-15 Step 1: $172,075
Maximum:  GS-15 Step 10: $183,500

So you would update the line below to look like this:

    {% include job/salary_range.html min="$172,075" max="$183,500" %}

To use the automatic salary ranges, leave the lines as-is.

🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}

{% comment %}{% include job/salary_range.html min="" max="" %}{% endcomment %}

**Salary range:** GS-12 ($86,962 to $140,713)

Your salary, including base and locality, will be determined upon selection, dependent on your actual duty location. Please note the maximum salary available for the GS pay system is $191,900. For specific details on locality pay, please visit [OPM's Salaries & Wages page](https://www.opm.gov/policy-data-oversight/pay-leave/salaries-wages/) or for a salary calculator [OPM's 2024 General Schedule (GS) Salary Calculator](https://www.opm.gov/policy-data-oversight/pay-leave/salaries-wages/2024/general-schedule-gs-salary-calculator/). You can find more information in our [compensation and benefits section]({{ '/join/compensation-and-benefits/' | url }}).

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Travel requirement:**
Occasional travel may be required up to 10%-20% per year.

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
**Work schedule:**
Full time.

**Appointment Type:**
This is a permanent position.

{% comment ------------------------------------------------------------------ %}
The next {% include ... %} line will pull in the appropriate text based on the
appointment type for this job. If you need to use different text, delete that
line and write your custom text in its place.
🔻🔻🔻🔻🔻
{% endcomment --------------------------------------------------------------- %}


{% comment %}{% include job/appointment_type.html %}{% endcomment %}

Learn more about the benefits of working at
[GSA](https://www.gsa.gov/portal/category/26702) and [TTS]({{ '/join/compensation-and-benefits/' | url }}).

## Role summary

{% comment %}🔻🔻🔻🔻🔻{% endcomment %}
As a Contact Center Program Analyst in TTS, you’ll assist the contact center in analyzing call metrics and other data provided by systems or contractors. TTS has a wide range of programs that further the organization’s mission, many of which operate on a reimbursable basis, including the USAGov Contact Center. You’ll assist the contact center team in reconciling the contract budget for the program after reviewing invoices. To meet these goals, you’ll iterate on current processes and participate in establishing new and more efficient ways to operate at the contact center. Success in this role requires analytical skills, organizational & policy knowledge, an aptitude for relationship building - especially with our internal partners, and a love of spreadsheets!

## Key objectives
<!-- markdownlint-disable MD033 -->
<ol type="1" class="key-objectives-list">
  <li>
    Identify improvements in operational problems
    <ul>
      <li>
        Plan or direct, special projects to identify operational problems, evaluate solutions, and recommend actions within the contact center.
      </li>
      <li>
        Independently or collaboratively conduct analytical studies of functional activities or programs.
      </li>
      <li>
        Work with the team to set and meet quality standards for any product you build.
      </li>
    </ul>
  </li>
  <li>
    Track and monitor Contact Center initiatives
    <ul>
      <li>
        Monitor the sequence and timing of the program or organizational milestones on contact center initiatives.
      </li>
      <li>
        Prepare or conduct briefings for higher-level management, including analysis, recommendations or action plans, and guidance for implementation.
      </li>
    </ul>
  </li>
  <li>
    Track and monitor Contact Center initiatives
    <ul>
      <li>
        Review information, reconcile conflicting data, and devise new or modified methods to analyze findings.
      </li>
      <li>
        Develop recommendations and proposals.
      </li>
      <li>
        Analyze and develop statistical data to improve the efficiency and effectiveness of programs or internal support operations for contact center quality management.
      </li>
      <li>
        Prepare or conduct briefings for higher-level management, including analysis, recommendations or action plans, and guidance for implementation.
      </li>
      <li>
        Identify and develop data for use in managing contact center programs.
      </li>
      <li>
        Thoroughly review contact center invoices to ensure accuracy.
      </li>
    </ul>
  </li>
</ol>
<!-- markdownlint-enable MD033 -->

{% comment ------------------------------------------------------------------ %}
Key objectives are automatically converted from the information provided at the
top of the page. The automatic conversion helps ensure that all of our postings
are consistent. If you do not want to use the automatic template, delete the
line below that says {% include job/key_objectives.html %} and add your custom
content in its place.
{% endcomment --------------------------------------------------------------- %}

{% comment %}{% include job/key_objectives.html %}{% endcomment %}

## Qualifications

Provide as much detail as possible on your resume so that we can evaluate your
previous experience. Follow our
[guidance on creating a federal style resume.](https://join.tts.gsa.gov/resume/)

Failure to provide required information may result in disqualification.

For each job on your resume, provide:

- The exact dates you held each job (from month/year to month/year or “present”)
- Number of hours per week you worked (if part time)

**SPECIALIZED EXPERIENCE REQUIREMENTS:**

To qualify, you must have one (1) year of specialized experience at the next
lower GS-grade (or equivalent). Specialized experience is defined as follows:

- Demonstrate use of evaluative and analytical methods to identify and measure progress;
- Revise methods and develop new approaches to information gathering;
- Plan, schedule, and lead complex projects using project management techniques;
- Identify opportunities for improvement based on an organization’s mission, practices, and procedures.


## How to Apply

{% comment %}{% include job/apply_button.html %}{% endcomment %}

Submit a complete online application prior to Tuesday, September 24th, 2024, at 11:59 pm ET. Please fill out all applicable fields. [Click here to apply.](https://www.usajobs.gov/job/808940800).

**Need Assistance in applying or have questions regarding this job opportunity, please email the TTS Talent Team at [jointts@gsa.gov](mailto:jointts@gsa.gov).**
