# logo_reco
Usage of logo recommendation exe file

***Quick Start***

**step1: unzip the file**
<pre>
<code>
tar -xvf logo_reco.tar
</code></pre>

**step2: run file**
<pre>
<code>
(base) root@----------:/home/logo/company/dist/logo_reco# ./logo_reco example_images/
torchvision/io/image.py:13: UserWarning: Failed to load image Python extension: ''If you don't plan on using image functionality from `torchvision.io`, you can ignore this warning. Otherwise, there might be something wrong with your environment. Did you have `libjpeg` or `libpng` installed before building `torchvision` from source?
torch/_jit_internal.py:853: UserWarning: Unable to retrieve source for @torch.jit._overload function: <function _DenseLayer.forward at 0x7f787c339550>.
  warnings.warn(
torch/_jit_internal.py:853: UserWarning: Unable to retrieve source for @torch.jit._overload function: <function _DenseLayer.forward at 0x7f787c352820>.
  warnings.warn(
Logo recommendation result is save to output.csv.
0:00:01.847276 sec
0:00:00.183710 seconds per image
</code></pre>

1. Output.csv File
   - The file named Output.csv contains the names of the images and their corresponding recommendation scores, sorted in descending order. Higher recommendation scores indicate logos that are recommended with higher priority. The example_output.csv file in github is the example format of output.csv.

2. Execution Time
   - Upon termination of the executable file, the execution time is displayed. The execution time per image is calculated by dividing the total execution time by the number of images.

3. Image Directory for Input
   - Inside the image directory address provided to the executable file, only image files should be present (preferably in JPG format).

