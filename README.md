
To update branches with changes from LimeSurvey (`vendor` is LimeSurvey repo
at Github, `origin` is Survos clone of it at Github):

If it's not already there:

    git remote add vendor git://github.com/LimeSurvey/LimeSurvey.git

Then:

    git checkout master
    git pull vendor master
    git push origin master
    git checkout Yii
    git pull vendor Yii
    git push origin Yii
