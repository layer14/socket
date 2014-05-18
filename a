from socket import *
import time
hour=raw_input("hour :")
mini=raw_input("min : ")
sec=raw_input("sec : ")

send =hour
send += mini
send += sec
s=socket(AF_INET,SOCK_STREAM)
s.connect(('127.0.0.1',7798))	#Need Change IP
s.send(send)
print send
s.close()
#send

