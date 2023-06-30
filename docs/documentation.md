# onp.base.template

## Metadata
| attribute               | value                                         |
| ----------------------- | --------------------------------------------- |
| pattern-id              | onp.base.template                             |
| pattern-name            | base template                                 |
| pattern-version         | 1.0.0                                         |
| pattern-description     | When you use AWS IAM Identity Center (successor to AWS Single Sign-On) to centrally manage single sign-on (SSO) access to all of your Amazon Web Services (AWS) accounts and cloud applications, reporting and auditing those assignments through the AWS Management Console can be tedious and time consuming. This is especially true if you’re reporting on permissions for a user or group across dozens or hundreds of AWS accounts.

For many, the ideal tool to view this information would be in a spreadsheet application, such as Microsoft Excel. This can help you filter, search, and visualize the data for your entire organization, managed by AWS Organizations.

This pattern describes how to use AWS Tools for PowerShell to generate a report of SSO identity configurations in IAM Identity Center. The report is formatted as a CSV file, and it includes the identity name (principal), identity type (user or group), accounts the identity can access, and permission sets. After generating this report, you can open it in your preferred application to search, filter, and audit the data as needed. The following image shows sample data in a spreadsheet application.

                        |
| organisation-id         | nc                                            |
| pattern-categories      | bootstrap                                     |

## What is this pattern?
This pattern is a basic template, modify it as you see fit

![](./diagrams/res/AWS_IAM_Report.png)

## What are the use cases?
This pattern is a basic template, modify it as you see fit

## Variables

| Variable               | Source                                         | Value |
| -----------------------| --------------------------------------------- | ------|
| Var1                   | SSM Parameter | onp/bootstrap/base-template|
