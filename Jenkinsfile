pipeline{
    agent any
    parameters{
        choice(name: "VERSION", choices: ["1.1.0", "1.1.1"])
    }
    stages{
            stage("testing"){
                steps{
                    echo "works"
                }
            }
    }

}
