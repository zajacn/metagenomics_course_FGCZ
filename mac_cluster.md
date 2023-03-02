How to log in to the cluster step by step.

1. Open the search window (Command + T) and type in "Terminal". Click enter and a black window will open up.
2. Sign into fgcz-genomics.uzh.ch server by typing: ssh my_bfabric_name@fgcz-genomics.uzh.ch. Replace my_bfabric_name with your actual bfabric name.
3. After you clicked enter it will ask you to enter a password. Please enter your password for bfabric. Note it will not be showing anything while you are typing.
4. Once you enter the cluster it will show (your_name@fgcz-h-176) in the left corner.
5. If your name is:  - please also do the following. Type in ssh fgcz-h-900. And then enter.
6. Now you need to navigate to your folder. You can do that by copying and pasting the following lines of code. Please replace your name when necessary. Use your bfabric username.

cd /scratch/p29934/my_bfabric_name/
source /usr/local/ngseq/miniconda3/etc/profile.d./conda.sh
conda activate metagenome-atlas

Now you should see the following the left hand corner:
(metagenome-atlas) your_bfabric_name@fgcz-h-176:/scratch/p29934/my_bfabric_name/$ 
OR 
(metagenome-atlas) your_bfabric_name@fgcz-h-900:/scratch/p29934/my_bfabric_name/$ 
OR 
(metagenome-atlas) your_bfabric_name@fgcz-h-911:/scratch/p29934/my_bfabric_name/$

If you don't see it, please let me know.
