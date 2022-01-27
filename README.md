# tango_with_django_project

“Tango with Django: A beginner’s guide to web development Chapter1-10

Requirement: We recommend that you work through all 20 chapters in TWD, however only your work on the first 10 chapters will be assessed. The development of your Rango application will account for 10% of your overall mark for the course. Successful completion of Rango will give you the skills that you need to work on the ITECH team project later, which accounts for 40% of your overall mark.

Working on Rango – Important Guidance The following guidelines are very important: be sure to read them carefully as they relate to the assessment of your Rango application.

You MUST make regular commits to your Git repository: AT LEAST once per chapter. We will be looking for evidence of regular commits when it comes to marking your Rango application.

You should ensure that any messages are conveyed exactly as described in TWD. For example, if your web page is supposed to include the message “Rango says hello world” then you must include exactly that message, and not “Rango says hey there” or “Rango says Hello World”. Similarly, files must be named exactly as stated – if you are required to include an image rango.jpg, this MUST be the filename and not Rango.JPG, for example. Automated testing will be carried out when it comes to marking your Rango application (see Chapter 18 of TWD) and you may lose marks if tests fail due to inconsistencies of the types described here.

We expect you to do the exercises at the end of the chapters in TWD (up to Chapter 10) – some of the automated tests are based on successful completion of these exercises.

You may find completed versions of Rango in various places on the web. If you download such a version and submit it as your own developed application, you will find that will not score highly for this exercise. This is because the automated tests are specifically designed so that they check out the step-by-step development of your application for this year – automated tests have been updated so they are not the same as last year. As the app changes over time, some tests from earlier chapters will fail. This is why it is so important to commit regularly (and at least once per chapter) because we will run our tests against all versions of your code in your commit history.

To explain this latter point further, suppose you have two commits of your code: one at time point A, and one at the later time point B, and suppose that automated test T is to be run against your code. As long as test T passes on at least one of versions A and B, you will be given the mark for this test.

Automated testing

Automated testing of your Rango application (taking code from your Github repository) will be carried out as follows:

End of week 7: The automated tests for Chapters 3-10 will be run on your Github repository and this time the results of running these tests will form the basis of your mark for the Rango application. You will again receive a summary (via an automated email) of the tests that you passed and those that you failed.

Rango development schedule

By the end of week 7 you should have completed the development of your Rango application up to the end of Chapter 10, as marking will take place at this time. As a guideline to help you plan your work, our expectation is that you will have completed the chapters as described in the “Labs Briefing” document in Moodle.

You are of course free to develop Rango ahead of this recommended schedule, but you should make sure that you do not fall behind.

Carrying out your own testing

The automated tests we will carry out on your code closely follows those provided in the book. We strongly recommend you carry out your own testing to ensure a good mark! This will allow you to gain feedback on how many tests you are passing and failing in advance of deadline. The automated tests that will be executed after the two Rango checkpoints will include those in the following Github repository https://github.com/maxwelld90/tango_with_django_2_code/. There will additionally tests such as the number of commits you did, the time intervals between commits.

It is highly recommended to run tests yourself in order to gain frequent and prompt feedback on the development of your Rango application.

How to submit

You should provide details of the location of your Github repository before the deadline on Rango Coursework: 24 February at 4.30pm This information should be supplied via Moodle. We recommend that you submit the link to your GitHub repository as early as possible, so you can forget about this and complete the Rango application. No further action is needed if you have submitted your link ahead of time.

Marking scheme

When your automated tests are run after the deadline, you will gain 1 mark for each test passed and 0 marks for each test failed (or terminated early due to an error). The total marks you gained will then be expressed as a percentage of the total number of tests N (currently N=60 though the final number of tests may vary slightly from this). This percentage will then be converted to a band which will be your mark for this component of the assessment.

Your percentage P will then be adjusted to take account of the number of commits C that you made. Since you are supposed to commit at least once per chapter, you should have at least 8 commits from Chapters 3-10. Your overall percentage Q for checkpoint 2 will then be P multiplied by min{C,8}/8. So, for example, if you made only 4 commits, Q will be P divided by

We will also be checking commit times. Commit times will not be part of your final grade, but allow us to detect plagiarism. For instance, a GitHub repository where all commits were made on the same day and over one week, will be flagged, and we will closely inspect source code, commit messages and history to determine course of action.
Common pitfalls

Based on prior experience, there are some scenarios that cause the tests not to run properly. We want to avoid a situation where you have done a lot of work developing Rango, but then find that you are passing none of the tests! You will be able to determine yourself if this is likely to happen by running the tests for yourself (see under “Carrying out your own testing”, above). There are some common reasons as to why the tests might not run properly, so if you are in this position it would be worth checking the following list to see if any of these reasons apply to you:

• You are running the tests from within a Dropbox folder (or similar cloud service provider) – it is more reliable to run the tests from a local drive or networked drive. • You receive the following error: “fatal: destination path 'temporal' already exists and is not an empty directory” – delete the folder “temporal”. • Your code is not in the master branch of your Github repository. • You committed your virtual environment – you must not do this. • You gave an incorrect Github URL. • Your Github repository is private – it must be public! • You developed Rango on PythonAnywhere – You should ensure that Rango can be deployed on localhost before you make your Git commits. • You have omitted to include init.py in the relevant project folders (thus git add has not picked up all the files that should be committed). • The module manage.py is missing from one of the commits – this could cause all of the tests to fail. • The module urls.py is missing from one of the commits – this could cause all of the tests to fail. • Your repository setup is unexpected. Refer back to the Environment Set up document for an explanation as to how your repository should be structured on Github. • The process timed out – this can happen if you made far too many commits (typically over 40). It is recommended to commit early and commit often (at least once per chapter), but you must not take this to excess! Try to aim for between 8-20 commits.
 
