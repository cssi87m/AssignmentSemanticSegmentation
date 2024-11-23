# How to Run

first you need to download the checkpoint at 
https://drive.google.com/file/d/17pjd2Ur4TtFqv50ipmOhvM_C3Vo4_dZu/view?usp=sharing

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