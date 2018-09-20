pipeline {
  agent any
  stages {
    stage('Create PR') {
      steps {
        echo 'Create PR'
      }
    }
    stage('Write Chef Cookbook') {
      parallel {
        stage('Chef Cookbook') {
          steps {
            echo 'InSpec Profile'
          }
        }
        stage('Metadata.rb') {
          steps {
            echo 'Test'
          }
        }
        stage('Recipies') {
          steps {
            echo 'test'
          }
        }
        stage('Attrbutes') {
          steps {
            echo 'test'
          }
        }
        stage('ReadMe') {
          steps {
            echo 'test'
          }
        }
        stage('Libraries') {
          steps {
            echo 'test'
          }
        }
        stage('Files/Templates') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Unit Test') {
      parallel {
        stage('Syntax Check') {
          steps {
            echo 'test'
          }
        }
        stage('Chefspec') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Syntax Check') {
      parallel {
        stage('Syntax Check') {
          steps {
            echo 'test'
          }
        }
        stage('Cookstyle') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Lint Check') {
      parallel {
        stage('Lint Check') {
          steps {
            echo 'test'
          }
        }
        stage('Foodcritic') {
          steps {
            echo 'Test'
          }
        }
      }
    }
    stage('Code Review') {
      steps {
        echo 'Test'
      }
    }
    stage('Publish Cookbook') {
      steps {
        echo 'test'
      }
    }
    stage('Commit to Master') {
      steps {
        echo 'test'
      }
    }
  }
}