# Monitoring 101 (Linux)
Administration on monitoring linux



## Professional Profile

Highly skilled IT professional with a comprehensive understanding of various IT monitoring types and tools. Proven expertise in ensuring system availability, optimizing web performance, and enhancing application management. Adept at employing cutting-edge technologies to bolster security measures and streamline business activities. Strong analytical abilities coupled with a proactive approach to problem-solving.

## Skills

- Availability Monitoring
- Web Performance Monitoring
- Application Management
- Application Performance Management (APM)
- API Monitoring
- Real User Monitoring (RUM)
- Security Monitoring
- Business Activity Monitoring (BAM)
- Troubleshooting
- Cloud Integration

## Professional Experience

- IT Monitoring Specialist
- XYZ Tech Solutions

- Spearheaded availability monitoring initiatives, ensuring uninterrupted system uptime and performance.
- Implemented web performance monitoring strategies, optimizing web server functionalities and resolving errors promptly.
- Utilized APM tools to track application performance, preemptively identifying and addressing potential issues.
- Managed API monitoring processes, guaranteeing seamless third-party integration and minimal downtime.
- Conducted real user monitoring, analyzing user interactions to enhance overall website and application experience.
- Enhanced security monitoring protocols, fortifying network defenses against breaches and unauthorized access.
- Implemented BAM tools to track key business metrics, facilitating data-driven decision-making processes.


## Certifications

- Certified IT Monitoring Professional (CITMP)
- Advanced Web Performance Monitoring Certification (AWPMC)
- Certified Application Performance Management Specialist (CAPMS)
- API Monitoring Expert (APIME)
- Real User Monitoring Certification (RUMC)
- Certified Security Monitoring Analyst (CSMA)
- Business Activity Monitoring Specialist (BAMS)


## Conclusion

This resume emphasizes your expertise in IT monitoring without being copied from someone else. It highlights your skills, experience, and qualifications tailored to the IT monitoring field.

===============================================================================================================

# Let's go more in details about Monitoring

## 1. How can you check what are the most memory intensive running processes ?

You can use 2 types of commands:

- top

It will display a dynamic real-time view of the running processes. 
By default, it sorts processes by CPU usage, but you can change it to sort by memory usage by pressing Shift + M. This will reorder the processes with the highest memory usage at the top.

- ps aux --sort=-%mem | head

It will lists all processes sorted by memory usage, with the most memory-intensive processes displayed at the top. It uses the -%mem flag to sort by memory usage percentage.
