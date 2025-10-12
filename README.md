This repository is a Perl script created to be run on the linux command line. After been cloned follow the following steps to flash an already built project using west or by running before zephyr-build script.

Installation (Ubuntu 20.04.1 LTS):

--Clone the repository--

`git clone git@github.com:harfuchcardenas/zephyr_flash.git`

--In order to flash a project to a board connected to a computer one must first build a project. To accomplish this one should clone the following repository--
(Detailed instructions can be found in the README.md file from
zephyr-build repository).

`git clone https://github.com/harfuchcardenas/zephyr_build.git`

`mv zephyr_flash/zephyr-flash zephyr_build/`

`rm -rf zephyr_flash`

`cd zephyr_build`

--Give execution permissions--

`chmod +x ./zephyr-flash`

--Run script--

./zephyr-flash
