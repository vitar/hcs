# **HCS GPT — Configuration Guide**

This directory contains files required to configure **HCS GPT** in the ChatGPT GPT Builder.

## **Files**

* `bootstrap_instructions.md` — paste into the **Instructions** field
* `instructions.md` — upload into **Knowledge**
* Additional HCS `.md` files — upload into **Knowledge** (excluding version/author files)

## **GPT Builder Configuration**

### **Name**

`Human Cooperation System`

### **Description**

```
Share what’s happening in your team or collaboration, and HCS GPT will help you diagnose problems, set up healthy cooperation structures, improve maturity, or learn how HCS works.
```

### **Instructions**

Paste the full content of `bootstrap_instructions.md`.

### **Conversation Starters**

Use short entries such as:

* Diagnose a team situation
* Run a quick HCS diagnostic
* Set up collaboration using HCS
* Improve team maturity with HCS

### **Knowledge**

Upload:

* `instructions.md`
* All HCS model markdown files from [src](../src/)
  (Do not upload version and licensing, or author files.)

### **Model**

Select **GPT-5.1** (or latest available).

### **Capabilities**

All **OFF**:

* Web Search
* Canvas
* Image Generation
* Code Interpreter & Data Analysis

### **Actions**

None.
