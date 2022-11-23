Installation Links:

Cent OS VM IMAGE : https://drive.google.com/file/d/1m3_fV04qJ1bJqT0LmklIm6ko2A0dpv65/view?usp=sharing
Vmware Software Download link : https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html
7zip Link : https://www.7-zip.org/download.html

======================================================
Post Installation to Start Hadoop services:
======================================================

 ==== Daemons to start ====
HDFS:
Linux> start-dfs.sh          # deamons - NameNode / DataNode / SecondaryNameNode
Linux> hadoop-daemon.sh start/stop namenode/datanode        # to start individual daemon without disturbing other daemon

MR/Yarn:
Linux> start-yarn.sh     # deamons - ResourceManager / NodeManager
Linux> yarn-daemon.sh start/stop resourcemanager/nodemanager    # to start individual daemon without disturbing other daemon
