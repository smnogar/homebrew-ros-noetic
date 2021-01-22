# Homebrew Tap for ROS Noetic

Helpful repo for building ROS Noetic

## Steps for Making Bottles

1. Build formula

   ```
   brew install --build-bottle smnogar/ros-noetic/FORMULA_NAME
   ```

2. Build bottle

   ```
   brew bottle --root-url=https://dl.bintray.com/snogar/bottles-ros-noetic FORMULA_NAME
   ```

3. Update formula with bottle SHA and commit

4. Upload bottle to `https://bintray.com/snogar/bottles-ros-noetic`. 

   * You will have to create a new package/version. 
   * Make sure to remove `--` if in file name. I.e. change `boost@1.73--1.73.0.big_sur.bottle.tar.gz` to `boost@1.73-1.73.0.big_sur.bottle.tar.gz`
   * Make sure to hit the publish button after uploading

5. 

