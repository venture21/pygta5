# 파이썬을 활용하여 GTA5 플레이하기

Python을 사용하여 GTA 5를 플레이하는 것에 대한 연구는 자율주행차 및 기타 차량을 만드는 것을 주 목적으로 한다. 

우리는 게임 코드 자체로 작업하기 보다는 데스크탑에서 직접 프레임을 읽는다. 이것은 단지 GTA5만을 위한 작업 뿐만 아니라, 보다 더 많은 게임과 함께 작동하며 영상을 입력하고 키를 출력하는 방식의 프레임을 기반으로 하는 모든 것에 적용할 수 있다.

Currently, to use the latest version of this AI, you will need to run first "create_training_data.py," then balance this data with "balance_Data.py."

When creating training data, this works when you have the game in windowed mode, 800x600 resolution, at the top left of your screen. You need this for both training and testing. Eventually we can go off the window's name, but, for now, the current code wants the window in the corner.

Do this for as many files/training samples as you wish. I suggest 100K+ after balancing, but the more the merrier.

Next, Train the model with train_model.py.

Finally, use the model in game with test_model.py. 

...you'll probably want to poke into the tutorials here: https://pythonprogramming.net/game-frames-open-cv-python-plays-gta-v/. If you need tutorials on deep learning, or tensorflow, or tflearn, see here: https://pythonprogramming.net/tensorflow-introduction-machine-learning-tutorial/

Do you know of some relevant papers/research/models for this project? Share with us here: https://github.com/Sentdex/pygta5/issues/11
