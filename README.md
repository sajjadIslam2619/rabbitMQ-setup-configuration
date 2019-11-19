# rabbitMQ-setup-configuration
rabbitMQ in windows

# Download and Install :
Visit this link (https://www.rabbitmq.com/install-windows.html) the process described in the given link briefly given here. 
1. First need to download Erlang(64 bit)[https://www.erlang.org/downloads]
Important: the Erlang installer must be run using an administrative account otherwise a registry key expected by the RabbitMQ installer will not be present.
2. Download rabbitmq-server-3.8.1.exe from https://www.rabbitmq.com/install-windows.html

The RabbitMQ service starts automatically. You can stop/reinstall/start the RabbitMQ service from the Start Menu. 
There might be some windows specific issue. Check this link : https://www.rabbitmq.com/windows-quirks.html

# Check control panel in localhost :
1. First need to enable management plugin. Go to the directory : C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.1\sbin and open cmd here. Run comand : rabbitmq-plugins enable rabbitmq_management
2. Check in the browser : http://localhost:15672/ (user: guest, pass: guest)
you can also visit : https://www.rabbitmq.com/management.html

# sample "Hello World" project in java : 
1. https://www.rabbitmq.com/tutorials/tutorial-one-java.html

