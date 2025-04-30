# Portable Stimulus Standard (PSS) Version 3.0

## Overview

The Portable Stimulus Standard (PSS) Version 3.0, released in August 2024 by Accellera Systems Initiative, defines a specification for creating a single representation of stimulus and test scenarios. This representation is usable across various execution platforms, including simulation, emulation, FPGA prototyping, and post-silicon testing. By specifying behaviors once, users can observe consistent behavior across multiple implementations. ([1](#1-accellera-unveils-portable-test-and-stimulus-standard-30-ushering-in-a-new-era-of-verification-efficiency), [2](#2-download-portable-stimulus-pss))

## Key Features

- **Declarative Environment**: PSS provides a declarative environment for abstract behavioral descriptions using actions, inputs, outputs, and resource dependencies. ([1](#1-accellera-unveils-portable-test-and-stimulus-standard-30-ushering-in-a-new-era-of-verification-efficiency))

- **Behavioral Coverage**: Support for behavioral coverage allows the generation of multiple scenarios from a single PSS specification, varying in action order and data. Coverage statements identify key action orders and data combinations that must be observed to exercise key functionality. ([1](#1-accellera-unveils-portable-test-and-stimulus-standard-30-ushering-in-a-new-era-of-verification-efficiency))

- **Enhanced Language Constructs**: Introduces new features such as string methods, sub-string operators, support for collections of reference types, platform qualifiers on function prototype declarations, and comments in template blocks. ([3](#3-pss-30-public-review-draft-now-available---portable-stimulus-30-public-review-feedback---accellera-systems-initiative-forums))

- **Cooperative Multitasking**: Support for yielding control with cooperative multitasking enables more efficient execution of test scenarios. ([1](#1-accellera-unveils-portable-test-and-stimulus-standard-30-ushering-in-a-new-era-of-verification-efficiency))

- **Address Space Group**: Introduces an address space group to allow multiple address spaces to share common storage elements. ([3](#3-pss-30-public-review-draft-now-available---portable-stimulus-30-public-review-feedback---accellera-systems-initiative-forums))

- **Formal Semantics**: Includes a formal semantics of behavioral coverage annex to provide a precise definition of coverage concepts. ([1](#1-accellera-unveils-portable-test-and-stimulus-standard-30-ushering-in-a-new-era-of-verification-efficiency))

## Applications

PSS 3.0 is designed to facilitate the generation of diverse implementations of scenarios that run on various execution platforms. It captures verification intent that can be analyzed to produce a broad spectrum of valid scenarios, enhancing the efficiency and effectiveness of the verification process. ([1](#resources))

## Resources

- [Download the PSS 3.0 Language Reference Manual](https://www.accellera.org/images/downloads/standards/pss/Portable_Test_Stimulus_Standard_v3.0.pdf)

- [Accellera Portable Stimulus Working Group](https://accellera.org/activities/working-groups/portable-stimulus)

- [Accellera Portable Stimulus Community](https://accellera.org/community/portable-stimulus)

---

### References

##### 1. [Accellera Unveils Portable Test and Stimulus Standard 3.0, Ushering in a New Era of Verification Efficiency](https://www.accellera.org/news/press-releases/402-accellera-unveils-portable-test-and-stimulus-standard-3-0-ushering-in-a-new-era-of-verification-efficiency?utm_source=circuitnext.com)

##### 2. [Download Portable Stimulus (PSS)](https://www.accellera.org/downloads/standards/portable-stimulus?utm_source=circuitnext.com)

##### 3. [PSS 3.0 Public Review Draft Now Available - Portable Stimulus 3.0 Public Review Feedback - Accellera Systems Initiative Forums](https://forums.accellera.org/topic/7811-pss-30-public-review-draft-now-available/?utm_source=circuitnext.com)

Feel free to explore the provided resources for more detailed information on PSS Version 3.0.
