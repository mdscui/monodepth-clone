# monodepth
Trying to debug training monodepth (https://github.com/mrharicot/monodepth) in Tensorflow on Windows. Error occurs because path is not found and posted on stackoverflow regarding printing out the result of join.

Running the following should start training:

```shell
python monodepth_main.py --mode train --model_name my_model --data_path D:/source/data/ --filenames_file D:/source/kitti_train_files.txt --log_directory ~/tmp/
```