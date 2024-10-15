*This is a template repository for this organization. Start by replacing the placeholder for the project name with its actual title.*

# [Development of the control process for an artificial intelligence-based boiler filter system]

## Summary
| Company Name | [University of Tartu](https://website.link) |
| :--- | :--- |
| Development Team Lead Name | [Tauri Tätte](https://profile.link) |
| Development Team Lead E-mail | [tauri@ut.ee](mailto:tauri@ut.ee) |
| Duration of the Demonstration Project | month/year-month/year |
| Final Report | [Example_report.pdf](https://github.com/ai-robotics-estonia/_project_template_/files/13800685/IC-One-Page-Project-Status-Report-10673_PDF.pdf) |

### Each project has an alternative for documentation
1. Fill in the [description](#description) directly in the README below *OR*;
2. make a [custom agreement with the AIRE team](#custom-agreement-with-the-AIRE-team).

# Description
## Objectives of the Demonstration Project

The project aims to create a highly durable power supply unit for electrofilters, utilizing digital feedback and machine learning capabilities. For this purpose, the Mitsubishi FX5U series PLC was selected to generate a pulse power signal, with a feedback speed of under 1 ms. The example demonstrates how to control a pulse power supply (half-bridge power supply) using two high-speed outputs (Y1 and Y2). The transformer is not equipped with a permanent load, and to protect the system, idle parameters are learned in advance.

## Activities and Results of the Demonstration Project
### Challenge
Since the device needs to be used in different environments and conditions, it is not possible to manually tune the device for each installation. The outputs of the control system depend on the filter's capacitance, which varies with the environment. Therefore, we implemented a solution designed to last long-term (expected 30–50 years). The power system is controlled by a PLC (industrial computer) through its pulse train outputs (PTO) (Figure 2). All data processing (including machine learning) is done at the PLC level. Since the device must be able to operate under cyclic heating, one crucial control function is the device's ability to quickly recover after a restart or power outage. This ensures the device returns to the previously learned long-term stable values (temperature/PTO) (Figure 1).

### Data Sources
*Please describe which data was used for the technological solution.*  
- [Source 1],
- [Source 2],
- etc... .

### AI Technologies
*Please describe and justify the use of selected AI technologies.*
- [AI technology 1],
- [AI technology 2],
- etc... .

### Technological Results

During laboratory testing and trials, it was found that our solution is capable of maintaining maximum voltage and current at the breakdown limit on the filter electrodes. The laboratory device demonstrated that such a controlled system could operate at maximum theoretical efficiency on a real device.

### Technical Architecture
*Please describe the technical architecture (e.g, presented graphically, where the technical solution integration with the existing system can also be seen).*
- [Component 1],
- [Component 2], 
- etc... .

![backend-architecture](https://github.com/ai-robotics-estonia/_project_template_/assets/15941300/6d405b21-3454-4bd3-9de5-d4daad7ac5b7)


### User Interface 
*Please describe the details about the user interface(i.e, how does the client 'see' the technical result, whether a separate user interface was developed, command line script was developed, was it validated as an experiment, can the results be seen in ERP or are they integrated into work process)*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Future Potential of the Technical Solution
*Please describe the potential areas for future use of the technical solution.*
- [Use case 1],
- [Use case 2],
- etc... .

### Lessons Learned
*Please describe the lessons learned (i.e. assessment whether the technological solution actually solved the initial challenge).*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Custom agreement with the AIRE team
*If you have a unique project or specific requirements that don't fit neatly into the Docker file or description template options, we welcome custom agreements with our AIRE team. This option allows flexibility in collaborating with us to ensure your project's needs are met effectively.*

*To explore this option, please contact our demonstration projects service manager via katre.eljas@taltech.ee with the subject line "Demonstration Project Custom Agreement Request - [Your Project Name]." In your email, briefly describe your project and your specific documentation or collaboration needs. Our team will promptly respond to initiate a conversation about tailoring a solution that aligns with your project goals.*
