# SRS IEEE LaTeX

A Software Requirements Specification document template written in LaTeX. It is created in conformance with the international standards stated in [ISO/IEC/IEEE 29148](https://standards.ieee.org/ieee/29148/6937/) .  

## General

The software requirements specification (SRS) is a specification for a particular software product, program, or set of programs that performs certain functions in a specific environment. The SRS may be written by one or more representatives of the supplier, one or more representatives of the acquirer, or by both.

It is important to consider the part that the SRS plays in the total project plan. The software may contain essentially all the functionality of the project or it may be part of a larger system. In the latter case typically there would be a requirement specification that states the interfaces between the system and its software portion, and places external performance and functionality requirements upon the software portion. Of course, the SRS should then agree with and expand upon these system requirements. The SRS indicates the precedence and criticality of requirements. The SRS defines all of the required capabilities of the specified software product to which it applies, as well as documenting the conditions and constraints under which the software has to perform, and the intended verification approaches for the requirements.

## SRS example outline

    1. Introduction
        1.1 Purpose
        1.2 Scope
        1.3 Product overview
            1.3.1 Product perspective
            1.3.2 Product functions
            1.3.3 User characteristics
            1.3.4 Limitations
        1.4 Definitions
    2. References
    3. Requirements
        3.1 Functions
        3.2 Performance requirements
        3.3 Usability requirements
        3.4 Interface requirements
        3.5 Logical database requirements
        3.6 Software system attributes
        3.7 Supporting information
    4. Verification
        (parallel to subsections in Section 3)
    5. Appendices
        5.1 Assumptions and dependencies
        5.2 Acronyms and abbreviations

## Notes

### Note 1

Examples of organizational approaches to requirements in an SRS include:

- System mode - some systems behave quite differently depending on the mode of operation. For example, a control system may have different sets of functions depending on its mode: training, normal, degraded or emergency.

- User class - some systems provide different sets of functions to different classes of users. For example, an elevator control system presents different capabilities to passengers, maintenance workers and firefighters.

- Objects - objects are real-world entities that have a counterpart within the system. For example, in a patient monitoring system, objects include patients, sensors, nurses, rooms, physicians, medicines, etc. Associated with each object is a set of attributes (of that object) and functions (performed by that object). These functions are also called services, methods or processes.

- Feature - a feature is an externally desired service by the system that may require a sequence of inputs to effect the desired result. For example, in a telephone system, features include local call, call forwarding and conference call. Each feature is generally described in a sequence of stimulus-response pairs.

- Stimulus - some systems can be best organized by describing their functions in terms of stimuli. For example, the functions of an automatic aircraft landing system may be organized into sections for loss of power, wind shear, sudden change in roll, vertical velocity excessive, etc.

- Response - some systems can be best organized by describing all the functions in support of the generation of a response. For example, the functions of a personnel system may be organized into sections corresponding to all functions associated with generating pay checks, all functions associated with generating a current list of employees, etc.

- Functional hierarchy - when none of the above organizational schemes prove helpful, the overall functionality can be organized into a hierarchy of functions organized by common inputs, common outputs or common internal data access. Data flow diagrams and data dictionaries can be used to show the relationships between and among the functions and data.

### Note 2

There are many notations, methods and automated support tools available to aid in the documentation of SRS requirements. For the most part, their usefulness is a function of organization. For example, when organizing by mode, finite state machines or state charts can prove helpful; when organizing by object, object-oriented analysis can prove helpful; when organizing by feature, stimulus-response sequences can prove helpful; and when organizing by functional hierarchy, data flow diagrams and data dictionaries can prove helpful.
