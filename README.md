# IFT220_Lab3
## Build a Domain Controller for a one tree Forest 

1. Deliverable
    1. The deliverable for the lab is the completed "DC Build Worksheet" from this repo

1. Prep
    1. Patch/update your VM
    1. When it's fully updated, take a VM snapshot so you can undo if something goes wrong
    1. Read the domain.ps1 script form Lab2 so you know what it's going to do
    1. Read the postdomain.ps1 script from Lab2 so you know what it's going to do
    1. Read the organizationalunits.ps1 script form Lab2 so you know what it's going to do
        1. **You should have edited the script to update the domainComponents (DC=)**
    1. Update your fork of Lab2
        1. Open PowerShell, CD into your lab 2 folder, and run the commands:
            1. `git remote add upstream https://github.com/ericcase/IFT220_Lab2.git`
            1. `git fetch upstream`
            1. `git checkout master`
            1. `git merge upstream/master`
            1. `git commit -m "merge upstream"`
            1. `git push`

1. Run 1st Script
    1. Run the doamin.ps1 script 
    1. **Read the prompts carfully**
    1. If you get errors, research them on your own before askig for help, restore to your snapshot as needed

1. Run 2nd Script
    1. Run the postdomain.ps1 script
    1. Check any errors, research them on your own before askig for help, restore to your snapshot as needed

1. Run 3rd Script
    1. Run the organizationalunits.ps1 script
    1. If you get errors, research them on your own before askig for help, restore to your snapshot as needed

1. (Optional) Configuring Time Synchronization for all Computers in a Windows domain
    1. https://www.altaro.com/hyper-v/configuring-time-synchronization-for-all-computers-in-windows-domain/
