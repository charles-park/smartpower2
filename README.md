FM Radio project
	FM radio with tea5767(fm module) and smartpower2.

	[Linux install guide]
		Install PlatformIO
		sudo apt-get install python-pip
		sudo pip install -U platformio
		platformio --version

	[Fork repo]
		https://github.com/hardkernel/smartpower2.git

	[Build & Upload]
		sudo platformio run
		sudo platformio run --target upload
		sudo platformio run --target uploadfs
