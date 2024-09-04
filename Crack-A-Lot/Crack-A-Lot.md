# Crack-A-Lot

1. So after opening the pcap file, I saw the protocol was something called EAPOl. Upon googling, found that it was something to with providing access via a network. So that means that there would be some data in those 2 sets of packets that were sent between the sender and receiever. 

2. Didn't get much more info on googling, so I asked ChatGPT how I could find the information hidden within, it suggested me to use tool like aircrack-ng.

3. Installed and ran aircrack-ng and it pieced together the flag that was hidden in those packets. 