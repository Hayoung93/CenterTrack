Fixed some code for running demo videos.

run example: `python demo.py tracking --load_model ../videos/coco_tracking.pth --demo /workspace/CenterTrack/videos/demo2.mp4 --save_video --debug=4`

Please refer to `xingyizhou/CenterTrack` for installation & etc., but it will cause some problem.

My suggestion (seaching among opened/closed issues):
install torch 1.4.0+cu100, torchvision 0.5.0+cu100 with pip
install DCNv2, following guide from original repo
re-install cv2
(also you might need to run apt install libgl1-mesa-glx, apt install libglib2.0-0)
run for demo! I believe that you can handle minor errors :)
