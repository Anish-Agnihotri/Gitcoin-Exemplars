<table>
<td width=100>
<img src='https://raw.githubusercontent.com/gitcoinco/gitcoinco/master/img/helmet.png'/>
</td>
<td width=800>
  <strong>Exemplar general discussion:</strong> What makes a good security bounty?
</td>
</table>

# What makes a good security bounty? 
A good security bounty is one that (unlike others) is fleshed out, well explained, and provides an adequate amount of detail in regards to the security issue/audit/etc. at hand. Similar to bug bounties, security bounties are generally retroactive, and are not geared towards solving a specific problem, but rather, hunting for one. For this reason, it's incredibly important to provide potentional bounty hunters with an appropriate scope and guideline for their testing. 

## What is a security bounty?
A security bounty is essentially a bounty in which bounty hunters are rewarded for either finding vulnerabilities within a platform, application, or task, or auditing the security of the former. It is an open-ended request which usually accepts multiple entries.

## What should be included in a security bounty?
Since security bounties have such a wide scope, there are various criterion which can be included to work towards an effective bounty description: 

### Introduction
The introduction of a security bounty in simple terms is a way for to reach out to prospective bounty hunters and tell them about your product, idea, task, application, etc. It's an easy, simple introduction to your organization or project and helps to immediately inform prospects of your current situation. For example:

```
Hello Bounty Hunters,

[your-organization] is a .... 
We've developed [your-idea/platform].
```

### Task
The task is the job at hand. This is a simple brief that describes the purpose of your bounty. For example:

```
The task is to find security issues within this repo: [some-repo]
```

### Application details
The application details describes any external links, dependencies, or requirements that may need to be referenced for the task. For example:

```
To complete the task, please view external instructions at [your-external-instructions].
Find sample architecture [here].
Note, [compiling|developing|setting up] will be involved.
```

### Severity OWASP model
Unique to security bounties, a severity OWASP risk rating model allows you to classify security vulnerabilities on the basis of their associated risk. In simpler terms, it essentially associates the likelihood and impact of a security concern on a graph allowing you to rate the risk in terms of Low, Medium, and High. This is useful when determining severity and payouts. For example: 

![Sample OWASP model](https://user-images.githubusercontent.com/23189295/44337157-8c7c0d80-a471-11e8-8231-ca1b113fd791.png)

### Payouts
The payouts details your compensation structure for security submissions in accordance to your OWASP model. For example: 

```
~ Critical: 0.5ETH
~ High: 0.3ETH
~ Medium: 0.2ETH
~ Low: 0.1ETH
```

### Submission 
Finally, submission details the method of how you want prospective bounty hunters to submit their work. With the security concern of publically reporting security vulnerabilities, it's essential to make certain you have a secure method of submission. For example:

```
Please email any findings to someone@someonescompany.com
```
