# alx-system_engineering-devops
TASKS
1.install_a_package.pp
	-
	This code defines a file resource with the path /tmp/school. The ensure parameter is set to 'file' to ensure that the file exists. The mode parameter sets the file permission to '0744'. The owner and group parameters specify the owner and group of the file as 'www-data'. Finally, the content parameter sets the file contents to 'I love Puppet'.

When you apply this Puppet code, it will create the file /tmp/school with the specified permissions, owner, group, and content.
1-install_a_package.pp
	In the code above, we define a package resource with the name 'flask'. The ensure parameter is set to '2.1.0' to specify the desired version of Flask. The provider parameter is set to 'pip3', indicating that Puppet should use pip3 to install the package
2-execute_a_command.pp
	n the code above, we define an exec resource with the title 'killmenow'. The command parameter specifies the command to be executed, which is pkill -f killmenow. The -f flag is used with pkill to match the entire command line of the process. The path parameter sets the search path for the command, including /usr/bin and /bin. Finally, the refreshonly parameter is set to true, indicating that the exec resource should only be triggered during a refresh event.