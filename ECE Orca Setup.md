# Install Orca
## All In One Go
Copy and Paste the following chunk of commands into your ECE Server Terminal
This may take multiple minutes to run
Make sure you are in the Home Directory (~/)

```
mkdir OrcaDownload
scp -P 55515 formulan@69.60.237.4:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part1.tar.xz ~/OrcaDownload
scp -P 55515 formulan@69.60.237.4:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part2.tar.xz ~/OrcaDownload
scp -P 55515 formulan@69.60.237.4:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part3.tar.xz ~/OrcaDownload
mkdir Orca
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part1.tar.xz -C ~/Orca
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part2.tar.xz -C ~/Orca
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part3.tar.xz -C ~/Orca
rm -rf OrcaDownload
echo 'export PATH=~/Orca:$PATH; export LD_LIBRARY_PATH=~/Orca:$LD_LIBRARY_PATH'  >> ~/.bash_profile
source ~/.bash_profile
echo "Done"
```

## Step By Step

**Make sure you are in the Home Directory in all Steps (~/)**

1. Make a Temporary Download Folder

```
mkdir OrcaDownload
```

2. Download the 3 "Zip" Files

```
scp a3dufres@iccad5:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part1.tar.xz ~/OrcaDownload
scp a3dufres@iccad5:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part2.tar.xz ~/OrcaDownload
scp a3dufres@iccad5:~/OrcaCopy/orca_5_0_4_linux_x86-64_openmpi411_part3.tar.xz ~/OrcaDownload
```

3. Make the Orca File to store the Software

```
mkdir Orca
```

4. Extract the "Zip" Files to the Orca Directory

```
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part1.tar.xz -C ~/Orca
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part2.tar.xz -C ~/Orca
tar -xf orca_5_0_4_linux_x86-64_openmpi411_part3.tar.xz -C ~/Orca
```

5. Remove the Temporary Download Folder

```
rm -rf OrcaDownload
```

6. Add Orca Path Variable

```
echo 'export PATH=~/Orca:$PATH; export LD_LIBRARY_PATH=~/Orca:$LD_LIBRARY_PATH'  >> ~/.bash_profile
source ~/.bash_profile
```








