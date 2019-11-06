# install Opencv 4 from source

## Observations

Try to be in OS level python and run cmake.

If we require for different virtual env, we have an option of symblink to that particular environment.

1. cd ~/.virtualenvs/cv/lib/python3.5/site-packages/   # This can be any ENV
2. ln -s /usr/local/python/cv2/python-3.5/cv2.so cv2.so

This worked for me

For installing in Unbuntu OS level

cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_PYTHON_EXAMPLES=ON -D INSTALL_C_EXAMPLES=OFF -D OPENCV_ENABLE_NONFREE=ON -D OPENCV_EXTRA_MODULES_PATH=~/opencv_contrib/modules -D BUILD_EXAMPLES=ON ..

After this make sure there is python interpreter as output.

Reference is:

<https://www.pyimagesearch.com/2018/08/15/how-to-install-opencv-4-on-ubuntu/>