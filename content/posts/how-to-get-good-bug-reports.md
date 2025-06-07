+++
title = 'How to get good bug reports: A guide for developers'
date = 2025-06-05T07:07:07+01:00
draft = true
tags = ["opensource", "foss", "bug","developer","guide"]
+++

# The Art of Getting Good Bug Reports: A Guide for Developers

## Introduction

All developers who have released software to the public have probably also struggled with vague, confusing, or completely unusable bug reports.

Reports like "It doesn't work!", or too little information, or too scattered information.

But the fact is that it is YOU as a developer who is largely responsible for getting good bug reports.

By being proactive, a developer can significantly improve the quality of the feedback that comes in, making the process less frustrating for everyone.

**Important: If you consistently get bad bug reports, the responsibility lies with you and NOT with your users. Most users want to help. Make it easy for them to give you the information you need, in the way you want it.**

## Templates Are a Must

**If you want consistent, complete bug reports, structured templates are mandatory.** It is the single most important improvement you can make - without a template you won't get the report in the format you want.

1. **Create mandatory report templates** for all channels where your project receives bug reports
2. **Require that important fields are filled in**
3. **Build up the template in a logical order**
4. **Show examples and give instructions in the template**

A good template creates just the right amount of structure and threshold in the reporting process to discourage quick, bad submissions, while not becoming a barrier for users who actually have problems.

In code collaboration platforms like GitHub, GitLab and similar, you can create issue templates with structure.

Here is [an example of a GitHub template](https://github.com/itiquette/gommitlint/blob/main/.github/ISSUE_TEMPLATE/bug_report.yml)

![alt](/images//bugreport1.png)

![alt](/images/bugreport2.png)

Here is another example template in pure Markdown:

```markdown
### What went wrong 
[Describe briefly and clearly what the problem is]
- What happened that wasn't right?
- Where in the program did the error occur?

### How it should work
[Explain what you thought would happen]
- What should have happened instead?
- How has it worked before?

### What happened instead
[Describe exactly what went wrong]
- What went wrong?
- Did you get any error message?

### How to recreate the problem
[List the exact steps to repeat the error]
1. Open '...'
2. Click on '....'
3. Scroll down to '....'
4. Now the error shows

### Images/Video (optional)
[Attach screenshots or video showing the problem]

### System information
 - Program version: [e.g. v2.1.3]
 - Device: [e.g. Desktop computer, iPhone 13, etc.]
 - Operating system: [e.g. Windows 11, macOS 12.3, iOS 16.2]
 - Browser (if relevant): [e.g. Chrome 108.0.5359.124, Safari 16.2]

### Other (optional)
[Add anything else that might be important]
- Does it happen every time or just sometimes?
- Only under certain circumstances?
- When did you first see the problem?
- Have you found any way to work around it?
```

**Warning**: Without mandatory templates, even well-meaning users will submit incomplete reports. A user cannot read your thoughts or understand your vision of what constitutes a "good" bug report.

## Focus on Code Collaboration Platforms

Modern development builds on systems like GitHub, GitLab and Bitbucket to handle bug reports.

These platforms offer advanced template features that should be your primary focus.

## Create a Positive Reporting Environment

Users are more likely to send thorough bug reports when they feel that their feedback is appreciated.

## Focus on Problems, Not the User

How you respond to bug reports strongly affects the quality of future reports.

Focus on the problem, not the user.

If the user is angry or frustrated and gets personal, continue to be professional and stick to the topic.

The task is to make better software, not to engage in unnecessary discussions.

### Examples of Problem-Oriented Language

Instead of: "You must have clicked the wrong button."
Use: "Describe which button you clicked on"

Instead of: "It works for me. You must be doing something wrong?"
Use: "I can't reproduce it on my end. What might be different in your environment."

Instead of: "That seems to be a user error."
Use: "We might be able to improve it and make it more intuitive. Tell me what you expected would happen?"

## Automate Information Collection

Don't rely solely on users to provide technical information.

If possible, add crash dumps, good logging systems etc.

Encourage the user to use screenshots or video of the error, if relevant.

## Ask the Right Questions

Guide users to provide specific information by asking direct questions:

- **What were you doing when the problem occurred?**
- **What happened that you didn't expect?**
- **What did you expect would happen instead?**
- **Can you recreate the problem? If so, how?**
- **Did you notice any error messages or unusual behavior?**
- **When did you first notice this problem?**
- **Has it happened more than once?**

## Distinguish Between Different User Types

A technical and non-technical user need to get different questions.

## Summary

Getting good bug reports is not about the user — it's about what you do to make it easier for the user to give that information, in the way you want it.

It makes it easier for everyone involved, and will help you focus on the actual problems.
