How to log in to the cluster step by step.

1. Open the search window (Command + Space) and type in "Terminal". Click enter and a black window will open up.
2. Sign into fgcz-genomics.uzh.ch server by typing: ssh my_bfabric_name@fgcz-genomics.uzh.ch. Replace my_bfabric_name with your actual bfabric name.
3. After you clicked enter it will ask you to enter a password. Please enter your password for bfabric. Note it will not be showing anything while you are typing.
4. Once you enter the cluster it will show (your_name@fgcz-h-176) in the left corner.

If you bfabric name is:	... copy paste the following into the command line and click enter:

```js
ssh fgcz-h-900
```

if your bfabric name is: ... copy paste the following into the command line and click enter:

```js
ssh fgcz-h-901
```

if your bfabric name is: ...  copy paste the following into the command line and click enter:

```js
ssh fgcz-h-902
```

5. Now you need to navigate to the directory you will be working in by typing the following lines of code, line by line into the command line, after every line pressing enter. Please replace your_bfabric_name with your actual name.

```js
cd /scratch/p35545/my_bfabric_name/ 
eval "$(/usr/local/ngseq/miniforge3/bin/conda shell.bash hook)"
conda activate gi_metagenome_atlas2.8.1
```

Now you should see the following the left hand corner: \
(gi_metagenome_atlas2.8.1) your_bfabric_name@fgcz-h-176:/scratch/p32710/my_bfabric_name/$ \
OR \
(gi_metagenome_atlas2.8.1) your_bfabric_name@fgcz-h-900:/scratch/p32710/my_bfabric_name/$ \
OR \
(gi_metagenome_atlas2.8.1) your_bfabric_name@fgcz-h-901:/scratch/p32710/my_bfabric_name/$ \
OR \
(gi_metagenome_atlas2.8.1) your_bfabric_name@fgcz-h-902:/scratch/p32710/my_bfabric_name/$ 

If you don't see it, please let me know.
