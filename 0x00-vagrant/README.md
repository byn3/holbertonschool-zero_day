# What I should have learned for this project

**What is a virtual machine?**  
*A virtual machine is a virtual machine. JK. Also known as a hypervisor if it's server related VMs. It is like an emulator but for a whole computer. You can run different OS's, inception for computers, a computer in a computer, no hardware. VMs are flexible, great for remote work. Helpful to prevent against attacks. Security- good to study how attacks work in a safe contained enviornment without endangering the real computer. Useful for testing since you can just crash your VM instead of real computer. Good for data management and server management. A virtual machine is basically a computer file that acts like a computer. Multiple VMs can run on a physical computer. VMs are very efficient in using the actual hardware. Cost saving. Reduces power and cooling and hardware and maintenance costs.* 

**What is vagrant?**  
*Vagrant is the shell. During peer learning day we went all philosophical... "What IS Vagrant?" We never came to a clear concise answer. Vagrant is the connection. It manages the VMs. A tool for working with virtual environments. Vagrant is a command line tool. You need a base image or Box for the VM that vagrant will manage. vagrant box add! Vagrant::Config.run do |config| config.vm.box = "ubuntu/trusty64". vagrant init. vagrant up. vagrant ssh.*  

**Who wrote Vagrant?**  
*Mitchell Hashimoto*  

**What is Ubuntu?**   
*A Linux OS that is free and open source. Suited for servers and desktops. Sponsored by Canonical Ltd.*  

**What does Ubuntu mean?**  
*Humanity in Nguni Bantu. Often translated as "I am because we are," and "humanity towards others". Zulu pronounciation.*  

**How to use VMs with Vagrant?**  
*Vagrant init. Configure the vm.box variable in the Vagrantfile. For my case I used ubuntu/tasty-64. Run Vagrant up. Vagrant SSH. And we gucci. https://www.vagrantup.com/intro/getting-started/.*  

**What does the command uname do?**  
*It prints out Linux on my command line. Actual definition: it prints the name, version, and other details about the current machine and OS.*  

**What is a zero-day?**  
*https://en.wikipedia.org/wiki/Zero-day_(computing) Day zero is the day someone learns about the vulnerability in the system. So the fewer days since day zero, the higher the chance no fix or mitigation has been developed. And even after a fix is made, there is still a high probability of damage because not every user applied the fix. SEVERE THREAT.*  


