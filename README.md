AdoVM Cyber Threat Monitoring Simulation Lab


Overview

This activity allows learners to simulate real-world cyber threats and practice basic system administration and security response using the AdoVM CTM Simulator.

You will configure a virtual environment, simulate attacks, analyze logs, and apply mitigation techniques.

Step 1: Download the Activity Files

	Access the GitHub repository below:
	https://github.com/xen0byt3/xen0byt3-CTM-Activity-8

Download the AdoVM CTM Simulator (.exe file) from the repository.

Step 2: Run the Simulator
	Open the downloaded .exe file
	Follow the on-screen terminal interface

Step 3: System Setup
	Update and Install Required Package
		sudo apt update
		sudo apt install [app_name]

Authentication Details
		Username: admin
		Password: admin
		Root account: No password

Step 4: Using the AdoVM CTM Simulator

	Inside the simulator, type:
	help

This will display the list of available commands.

Step 5: Activity Workflow

	Follow the steps in order:

		Set VM hostname
		Set IP address
		Check system status

	Simulate Cyber Attacks

		Run the following attack simulations:
		penetration
		scan
		brute-force
		malware
		ddos

Log Monitoring & Mitigation
	1. Check logs
	2. Stop SSH control services
	3. Verify that "Brute force login attempt" is removed from Active Threats
	4. Stop HTTP control services
	5. Verify that "DDoS on HTTP service" is removed
	6. Stop FTP control services
	7. Verify that "Malware upload attempt on FTP" is removed
	8. Enable FIREWALL

System should display:

	No active threats
Start HTTP services again to continue operations

Step 6: Quiz
	Navigate to the quiz section
	Target score: 35 points

If your score is too low or too high, repeat the activity to achieve the correct workflow.

Step 7: Export Logs

	Export your activity log:

		vm_activity_log.txt


[Submission Guidelines]

Choose one of the following:

Option 1 (Recommended)
	Upload your vm_activity_log.txt to your GitHub repository
	Add xen0byt3 as a collaborator
Option 2 (Most Recommended)
	Create a Pull Request containing your vm_activity_log.txt
