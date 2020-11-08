pipeline {
    agent any
    stages {
        stage('clean repository') {
            steps {
                bat "IF exist reminder_part1 ( rmdir /Q /S reminder_part1 )"
            }
        }
        stage('Run code') {
            steps {
                
                bat "C:/Users/alexk/AppData/Local/Programs/Python/Python38-32/python.exe reminder_part1/reminder.py"
            }
        }

    }
}
