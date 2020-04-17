Data Provider & PI Safe Haven User Guide 
=========================================

## :mailbox_with_mail: Table of contents:

* [**Introduction:** The Turing Safe Haven](https://github.com/DaisyParry/organise-spice-cupboard-/edit/master/testing.md#introduction-the-turing-safe-haven)
- [:mag_right: Definitions](#mag_right-definitions)

## :beginner: Introduction: The Turing Safe Haven

Welcome to the Turing Safe Haven tool. 

Safe havnes are secure research environments (SREs) used for analysis of sensitive datasets and are essential for research, giving data providers confidence that their datasets will be kept secure over the course of a project. **Before** the project can get started using a safe haven, you’ll need to have classified the data you’re using to understand its sensitivity, and how it should be handled - more on this later on.

The Safe Haven SRE design is aimed at allow groups of researchers to work together on projects that involve sensitive or confidential datasets at scale. Our goal is to ensure that you are able to implement the most cutting edge data science techniques while maintaining all ethical and legal responsibilities of information governance and access.

The data you are working on will need to be classified into one of five sensitivity tiers using the **Data Assesment App**, tier range from open data at Tier 0, to highly sensitive and high risk data at Tier 4. The tiers are defined by the most sensitive data in your project, and may be increased if the combination of data is deemed to be require additional levels of security. You can read more about this process in our policy paper: Arenas et al, 2019, arXiv:1908.08737.

The level of sensitivity of your data determines whether researchers will have access to the internet within the SRE and whether you are allowed to copy and paste between the secure research environment and other windows on your computer. This means researchers may be limited to which data science tools they are allowed to install. 

| Safe Haven sensitivity tier | Data features | Environment features |
| ---------------------------- | ------------ | -------------------- |
| Tier 0 | Open data or data with no negative consequences if it was to be published | Access from any device, copy and paste function enables, intenet enabled |
| Tier 1 | Data with very limited consequences if it was to be published, such as data being held back from being published for research advantage | Access from any device, copy and paste function enables, intenet enabled |
| Tier 2 | Commercially sensitive data & strongly pseudonymised personal data | Access from any device, copy & paste function disabled, internet disabled | 
| Tier 3 | Personal data with weak or no pseudonymisation,  more sensitive commercial or government data | Access from know spaces and manged devices only, internet disabled, copy & paste function disbaled, white listed packages only |
| Tier 4 | Very sensitive personal, commercial or government data | Access only from known dedicated secure rooms and devices, internet disabled, copy & paste function disabeled, stricter white listed packages |


Please read this user guide carefully and remember to refer back to it when you have questions. In many cases the answer is already here, but if you think this resource could be clearer, please let us know so we can improve the documentation for future users.


### :mag_right: Definitions

The following definitions might be useful during the rest of this guide

> **Secure Research Environment (SRE)**: the environment that you will be using to access the sensitive data.

> **Turing Safe Haven**: the overall project that details how to create and manage one or more SREs.
