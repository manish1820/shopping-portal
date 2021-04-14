pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
/*    tools{
     	nodejs 'nodejs'
    }
*/    

    stages{
        stage('build'){
            steps{
                echo 'this is the build job'
                sh 'npm install'
                sleep 4
            }
        }
        stage('test'){
            steps{
                echo 'this is the second job'
                sh 'npm test'
                sleep 9
            }
        }
        stage('package'){
            steps{
                echo 'this is the third job'
                sh 'npm package'
                sleep 7
            }
        }
    }
    
    post{
        always{
   pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
/*    tools{
        nodejs 'nodejs'
    }
*/    

    stages{
        stage('build'){
            steps{
                echo 'this is the build job'
                sh 'npm install'
                sleep 4
            }
        }
        stage('test'){
            steps{
                echo 'this is the second job'
                sh 'npm test'
                sleep 9
            }
        }
        stage('package'){
            steps{
                echo 'this is the third job'
                sh 'npm package'
                sleep 7
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    Connected, host fingerprint: ssh-rsa 0 4A:B3:D7:ED:28:D9:22:E4:1D:53:2D:9D:62:1E:26:3A:80:75:C7:03:1C:26:EC:20:78:7E:93:F5:E7:93:4B:20
Welcome to Ubuntu 18.04.5 LTS (GNU/Linux 5.4.0-1041-gcp x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Wed Apr 14 14:21:01 UTC 2021

  System load:  0.06              Users logged in:                1
  Usage of /:   8.3% of 96.75GB   IP address for ens4:            10.128.0.2
            }
        }
    }
    
    post{
        always{
   pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
/*    tools{
        nodejs 'nodejs'
    }   
*/      
    
    stages{
        stage('build'){    
            steps{
                echo 'this is the build job' 
                sh 'npm install'
                sleep 4      
            }
        }
        stage('test'){
            steps{
                echo 'this is the second job'
                sh 'npm test'
                sleep 9
            }
        }    
        stage('package'){
            steps{
                echo 'this is the third job' 
                sh 'npm run package'       
                sleep 7
            }
       }         echo 'this pipeline has completed...'
        }
        

