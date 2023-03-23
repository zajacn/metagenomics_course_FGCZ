This is a step by step list of instruction on how to log into the cluster from a windows computer.

1. Download Putty for the following link: https://www.putty.org/ \
2. Once you have installed Putty, you should open it up and see the following window:

![Putty](Putty_picture.jpeg)

3. Enter the following into the window:

- Host Name: fgcz-genomics.uzh.ch
- Port: 22
- Connection type: SSH

4. Click OPEN.
5. It will now ask you for your username. Provide it with your bfabric username. So for me it would be zajac. Click enter.
6. It will now ask you for your password. Provide it with your bfabric password. Note that while you are writing it will not show anything. So after you typed it just click enter.
7. You have now arrived. You should see (your_bfabric_name@fgcz-h-176:$) on the left hand side. 
If you bfabric name is: guerillot, lafortezza, niamhniv, copy paste the following into the command line and click enter:

```js
ssh fgcz-h-900
```

if your bfabric name is: nolan or tiozon or miachizzi copy paste the following into the command line and click enter:

```js
ssh fgcz-h-911
```

8. Now you need to navigate to the directory you will be working in by typing the following lines of code, line by line into the command line, after every line pressing enter. Please replace your_bfabric_name with your actual name.

```js
cd /scratch/p29934/my_bfabric_name/ \
source /usr/local/ngseq/miniconda3/etc/profile.d./conda.sh \
conda activate metagenome-atlas 
```

Now you should see the following the left hand corner: \
(metagenome-atlas) your_bfabric_name@fgcz-h-176:/scratch/p29934/my_bfabric_name/$ \
OR \
(metagenome-atlas) your_bfabric_name@fgcz-h-900:/scratch/p29934/my_bfabric_name/$ \
OR \
(metagenome-atlas) your_bfabric_name@fgcz-h-911:/scratch/p29934/my_bfabric_name/$ 

If you don't see the following, please let me know.

