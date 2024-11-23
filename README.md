# How to Run

first you need to download the checkpoint at 
https://drive.google.com/drive/folders/10mG52BJmC5fr7xMh9hBeHerVe8f2k9Nx?usp=drive_link

and then put that checkpoint folder ```checkpoint```

```sh
git clone https://github.com/cssi87m/AssignmentSemanticSegmentation.git
cd AssigmentDL
python infer.py --image_path {path_to_image}
or
python3 infer.py --image_path {path_to_image}
```

the result will be shown in  ```{path_to_image}_result.jpeg```

# Competition
https://www.kaggle.com/competitions/bkai-igh-neopolyp/leaderboard

<p align="center">
  <img src="result.png"  >
  
</p>