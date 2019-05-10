# OWASP Code Review Feedback Page

The purpose of this page is to record feedback and issues with the OWASP
Code Review Guide version 2.0. Whilst a lot of time was spent towards
the end of the project to remove these issues, and many issues were
removed. As with any collaborated document development, especially of a
document this size, there will be typos and the like, with technical
issues.

We appreciate the help of the community in providing feedback on any
issues spotted so that we can improve this document.

If you have access to the OWASP Wiki, please update this page with a
list of issues you have spotted. If you do not have access to edit the
wiki, then please e-mail the code review team at
<owasp-codereview-project@owasp.org>.

## Feedback to date

The following feedback items have been received so far regarding v2.0 of
the Code Review Guide.

|                                          |                                                                                                                                          |                                                                                                                                                                                                                                            |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Page Number                              | Issue Description                                                                                                                        | Suggested Resolution                                                                                                                                                                                                                       |
| 4                                        | Word 'thru' used twice                                                                                                                   | Change to 'through'                                                                                                                                                                                                                        |
| 7                                        | Typo 'project life cycle will that code reviews should be done'                                                                          | Change to 'project life cycle code reviews should be done'                                                                                                                                                                                 |
| 7                                        | Typo 'manfully feedback'                                                                                                                 | Change to 'meaningful feedback'                                                                                                                                                                                                            |
| 7                                        | Typo 'on the type of code review do you want to accomplish'                                                                              | Change to 'on the type of code review you want to accomplish'                                                                                                                                                                              |
| 7                                        | Typo 'can be assistance to you'                                                                                                          | Change to 'can assist you'                                                                                                                                                                                                                 |
| 7                                        | Typo 'whichh'                                                                                                                            | Change to 'which'                                                                                                                                                                                                                          |
| 7                                        | Typo 'prove code methods works'                                                                                                          | Change to 'prove code methods work'                                                                                                                                                                                                        |
| 7                                        | Typo 'in to the organizations'                                                                                                           | Change to 'into the organizations'                                                                                                                                                                                                         |
| 7                                        | Following section is unclear 'This book will also work as a reference guide for the code review as code is in the review process'        | Change to 'This book will also work as a reference guide for the secure review of code during the code review process'                                                                                                                     |
| 9                                        | Why does the numbering start at 5?                                                                                                       | This is due to it technically being the 5th section, though the previous sections are not clearly numbered. Is this an issue...?                                                                                                           |
| 10                                       | Sentence unclear 'If informed decisions are being made based on a measurement of risk in the enterprise, which will be fully supported.' | Change to 'If informed decisions are being made based on a measurement of risk in the enterprise, this risk based approach should be fully supported by feedback from code reviews.'                                                       |
| Numerious places (starting with page 13) | HIPPA spelt incorrectly (it's HIPAA)                                                                                                     | Change to HIPAA - 3 instances.                                                                                                                                                                                                             |
| 15                                       | Typo 'encase'                                                                                                                            | Change to 'in case'                                                                                                                                                                                                                        |
| 15                                       | Typo 'par-ticular'                                                                                                                       | Change to 'particular'                                                                                                                                                                                                                     |
| 18                                       | Typo 'Requirement 6.5 address'                                                                                                           | Change to 'Requirement 6.5 addresses'                                                                                                                                                                                                      |
| 44                                       | Issue with SQL 'Select custName, address1,address2,city,postalCode WHERE custID= '                                                       | Change to 'SELECT custName, address1 FROM cust_table WHERE custID= '                                                                                                                                                                      |
| 57                                       | Formatting of text 'fields, drop down lists, and other web components are properly validated.'                                           | This seems to be its own bullet point, however it should be a line continuation of the last bullet point.                                                                                                                                  |
| 60                                       | Sample 8.1 text needs to be changed from '‘’’flters.Add(new RequireHttpsAttribute());’’’'                                                | Change to 'flters.Add(new RequireHttpsAttribute());' (i.e. remove the ''' at either end)                                                                                                                                                   |
| 64                                       | Formatting issue with text 'However this can be hard to enforce. a. If possible give users the choice of band they wish to use.'         | Change to 'However this can be hard to enforce. If possible give users the choice of band they wish to use.' (i.e. remove the 'a.' and keep it all in the same paragraph.                                                                  |
| 68                                       | Formatting issues                                                                                                                        | A number of the bullet points have newlines where they are not needed (3rd, 4th & 5th bullet points).                                                                                                                                      |
| 68                                       | Session Fixation points should be bullet points and not numbered (numbers are wrong anyway).                                             | 2nd bullet point should be "All the session-ids should be generated by the application, and then stored in a pool to be checked later for. Application is the sole authority for session generation." - i.e. all 1 paragraph, no new line. |
| 68                                       | Formatting issue                                                                                                                         | 2nd bullet point under session fixation has an unnecessary new line.                                                                                                                                                                       |
| 72                                       | Typo with 'Another level of to help prevent XSS is to use an Anti-XSS library'                                                           | Change to 'Another level of help to prevent XSS is to use an Anti-XSS library'                                                                                                                                                             |
| 73                                       | Typo with 'OWASP_Zed_Attack_Proxy_Project'                                                                                           | Change to 'OWASP Zed Attack Proxy Project'                                                                                                                                                                                                 |
| 90                                       | Formatting issue                                                                                                                         | Need a newline (whitespace) before title "JBoss AS", and sample 11.8 appears mid-sentence                                                                                                                                                  |
| 90                                       | Formatting issue                                                                                                                         | Title "Oracle WebLogic" is at the bottom of the page, needs to be moved to the top of the next page.                                                                                                                                       |
| 91                                       | Formatting issue                                                                                                                         | Remove text "Principal object"                                                                                                                                                                                                             |