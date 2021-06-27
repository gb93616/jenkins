pipeline {

	agent any
	stages {
		stage("Checkout") {
			steps {
                echo "This is the checkout step"
			}
		}
		stage("build")
		       steps {
                echo "This is the build step"
		     {
		}
		stage("deploy") {
			steps {
                echo "This is the deploy step"
			}
		}
	}
}
post {
	always{
        echo "This will display always"
		//
	}
	success{
        echo "This will display on success"
		//
	}
	failure{
        echo "This will display on failure"
		//
	}
}
//
