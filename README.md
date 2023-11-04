# edix-S7L3
Simple pipeline for assignment

Edit 04-10-2023: This is terrible.
## Update TODO List:
- [ ] Better secret protection.
- [x] Creation and destruction of infrastructure needed.
- [ ] No script{} steps at all.
- [x] Minimizing Plugin/Groovy usage.
- [ ] When statements for defining workflow. (Might be needed if adjusting the pipeline for Powershell/PowershellCore/Bash).
- [ ] Proper Success and Failure Routines, Notification system usage.
- [ ] Multistage division.
- [x] Quick credential swap.
- [ ] Finding a way to keep the AWS credentials loaded without keeping the workspace.
- [x] Environment variable creation at runtime.
- [ ] Make it not depend on sh or powershell, or make it detect the host OS.
- [ ] Make it not break when naming the Job with a space. Example "MyJob" works fine, "My Job" literally breaks apart.
- [ ] Give the Lambda function some other task other than show off. The current sh block makes it unnecessarily uncompatible with Jenkins on Wind$ws.
- [x] Multi-run consistency.
- [ ] Reduced run time.
- [ ] Proper timeouts.
- [ ] ... lots of stuff to improve.

## Notes:
~~If not using a Student account, you might want to modify the CloudFormation template to change the Lambda's Execution Role.
Or just delete the Lambda function altogether and delete everything with AWS Steps.~~

THIS CLOUDFORMATION AND LAMBDA APPROACH IS OVERENGINEERED AND USELESS AND A WASTE OF TIME.

## Results
[Video](https://raw.githubusercontent.com/txrm/edix-S7L3/main/Video.mp4)
THIS BREAKS IF NOT ON LINUX/LINUX DOCKER WITH GIT INSTALLED.
THIS BREAKS IF USING NORMAL SHORT-LIVED AWS CREDENTIALS

### Screencaps
![result1](https://github.com/txrm/edix-S7L3/blob/main/screencaps/1.png?raw=true)
![result2](https://github.com/txrm/edix-S7L3/blob/main/screencaps/2.png?raw=true)
![result3](https://github.com/txrm/edix-S7L3/blob/main/screencaps/3.png?raw=true)
![result4](https://github.com/txrm/edix-S7L3/blob/main/screencaps/4.png?raw=true)
![result5](https://github.com/txrm/edix-S7L3/blob/main/screencaps/5.png?raw=true)
