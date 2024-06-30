Model upload using https://git-lfs.com
There is no dataset upload in data folder due to large memory overload.
Apache Kafka must be installed before even attempting to run the model.
1. Fire up Zookeeper and Kafka (assuming you've already had Kafka on your system).
2. Create two cmd prompt (recommend anaconda for virtual enviroment and package managemtn).
3. Run python consumer.py on one of the two cmd prompt.
4. Turn off all firewall setting (recommend)
5. Click one of the two local IP to redirect to web streaming (change site setting to allow everything if not secured notification shows up)
6. Run python python video_demo.py --pre model/model_best_qnrf.pth  --video_path Input/Test.mp4 (Delete --video_path Input/Test.mp4 if live feed is desired)
7. Enjoy the show.
