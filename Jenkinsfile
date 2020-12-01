pipeline{
    agent any
    
    stages{
        stage("Build"){
            steps{
                echo "checkout source code..."
            }
        }
		stage("Test"){
			steps{
				echo "Build the source..."
			}
		}		
		stage("Deploy"){
			steps{
				echo "Test your code..."
				echo "Deploy your package..."
			}
		}
    }
    post{
        success{
            echo "build is done..."
        }
    }
}
