properties([pipelineTriggers([pollSCM('* * * * *')])]
node{
    stage("1"){
        git branch:"main", url: "https://github.com/Hillelg-cloud/pycharm.git"
        bat "C:/Users/il_ro/AppData/Local/Programs/Python/Python310/python.exe date.py" 
    }
}
