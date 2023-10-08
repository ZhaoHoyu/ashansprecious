Steps to validate the communication between mac and win based on sokit(Mac mini) and other software(Win):
1.Prepare the hardware(Win-PC/Mac/Ethernet cable that link the two PC) and software(sokit/other software that can communicate with sokit 
2.IP configuration: 
1)Configure the IP of two PC in the same net segment.i.e.Mac: 192.168.43.1 / 255.255.255.0; Win:192.168.43.2 / 255.255.255.0
2)Configure the IP of sokit(server) and software in win (client)  the same as the IP of Mac. i.e. 192.168.43.1 port 9999(editable)
3.Connect i.e click the connect button on sokit.
4.Send command from sokit and check the response
------------------------------------------------------------------------------------------------
Method to execute sokit on Mac:
1.sokit executive file download link: https://github.com/rangaofei/SSokit-qmake/releases
// just download the ssokit.dwg 
2.Using homebrew install sokit
1)Using cmd prompt window running the cmd: brew tap rangaofei/saka(After install homebrew,if u have any question,search in web)
2)excutive the cmd:brew install sokit
3)running:sokit

