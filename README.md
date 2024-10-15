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

![backend-architecture](https://github.com/ai-robotics-estonia/Testing_an_Artificial_Intelligence_Based_Boiler_Filter_System_Control_Process/blob/main/diagram%20of%20the%20filter%20system.jpg)
Figure 1
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

![backend-architecture](https://github.com/ai-robotics-estonia/Testing_an_Artificial_Intelligence_Based_Boiler_Filter_System_Control_Process/blob/main/PLC%20program%20diagram.jpg)
Figure 2

### User Interface 

The user can continuously monitor the process (voltage and effective voltage) and learning parameters on the screen (HMI). During the process, additional readings were added to the system created in the previous project. The user can create and modify parameters if they have configuration rights.

### Future Potential of the Technical Solution

The sample solution is instructive in many fields, as no analogously controlled power device has been created before. The software solution can be reused in multiple scenarios. Since it is essential for the device to measure rapid changes in voltage and current at the output, there is only a rectifier in the high-voltage transformer output, which does not contain additional loads or capacitances. This provides a significant opportunity to create devices with digital feedback that have very high efficiency and low idle costs.

### Lessons Learned

Both the company and the developers are satisfied with the results of this solution. The results were even surprising, as such digital feedback transformer control has not been described anywhere before.


