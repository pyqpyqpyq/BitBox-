java -cp bitbox.jar unimelb.bitbox.Client -c list_peers -s localhost:8101 -i pyq@unimelb
java -cp bitbox.jar unimelb.bitbox.Client -c connect_peer -s localhost:8101 -p localhost:8112 -i pyq@unimelb
java -cp bitbox.jar unimelb.bitbox.Client -c disconnect_peers -s localhost:8101 -p localhost:8112 -i pyq@unimelb
#missing c/s/i option will cause the failure of execution