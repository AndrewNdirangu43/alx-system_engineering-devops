	# This is a directory with modules regarding tasks in 0x04-loops_conditions_and_parsing.
	# Modules include:
	
	1. > 0-RSA_public_key.pub:
	--------------------------

	You will soon have to manage your own servers concept page hosted on remote data centers. 
	We need to set them up with your RSA public key so that you can access them via SSH.

	Create a RSA key pair.

	Requirements:

	Share your public key in your answer file 0-RSA_public_key.pub
	Fill the SSH public key field of your intranet profile with the public key you just generated
	Keep the private key to yourself in a secure location,you will use it later to connect to your servers using SSH
	Some storing ideas are Dropbox, Google Drive, password manager, USB key. 
	Failing to do so will prevent you to access your servers, which will prevent you from doing your projects
	If you decide to add a passphrase to your key, 
	make sure to save this passphrase in a secure location, 
	you will not be able to use your keys without the passphrase
	SSH and RSA keys will be covered in depth in a later project.

	2. > 1-for_best_school:
	-----------------------
	
	Write a Bash script that displays Best School 10 times.
	
	Requirement:

	You must use the for loop (while and until are forbidden)
	
	3. > 2-while_best_school:
	-------------------------

	Write a Bash script that displays Best School 10 times.

	Requirements:

	You must use the while loop (for and until are forbidden)

	4. > 3-until_best_school:
	-------------------------

	Write a Bash script that displays Best School 10 times.

	Requirements:

	You must use the until loop (for and while are forbidden

	5. > 4-if_9_say_hi:
	-------------------

	Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.

	Requirements:

	You must use the while loop (for and until are forbidden)
	You must use the if statement

	6. > 5-4_bad_luck_8_is_your_chance:
	-----------------------------------

	Write a Bash script that loops from 1 to 10 and:

	displays bad luck for the 4th loop iteration
	displays good luck for the 8th loop iteration
	displays Best School for the other iterations

	Requirements:

	You must use the while loop (for and until are forbidden)
	You must use the if, elif and else statements

	7. > 7-clock:
	-------------

	Write a Bash script that displays the time for 12 hours and 59 minutes:
	display hours from 0 to 12
	display minutes from 1 to 59

	Requirements:

	You must use the while loop (for and until are forbidden)

	8. > 8-for_ls:
	--------------

	Write a Bash script that displays:
	The content of the current directory
	In a list format
	Where only the part of the name after the first dash is displayed (refer to the example)

	Requirements:
	
	You must use the for loop (while and until are forbidden)
	Do not display hidden files

	9. > 9-to_file_or_not_to_file:
	------------------------------

	Write a Bash script that gives you information about the school file.

	Requirements:

	You must use if and, else (case is forbidden)
	Your Bash script should check if the file exists and print:
	if the file exists: school file exists
	if the file does not exist: school file does not exist
	If the file exists, print:
	if the file is empty: school file is empty
	if the file is not empty: school file is not empty
	if the file is a regular file: school is a regular file
	if the file is not a regular file: (nothing)

	10. > 10-fizzbuzz:
	------------------
	Write a Bash script that displays numbers from 1 to 100.

	Requirements:

	Displays FizzBuzz when the number is a multiple of 3 and 5
	Displays Fizz when the number is multiple of 3
	Displays Buzz when the number is a multiple of 5
	Otherwise, displays the number
	In a list format
