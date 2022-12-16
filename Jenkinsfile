pipeline{
    agent any
    stages{
        stage("SH"){
            steps{
                echo "La version $(grep 'INT' release.yaml | cut -d: -f1) es:$(grep 'INT' release.yaml | cut -d: -f2)" 
                echo "La version $(grep 'PRE' release.yaml | cut -d: -f1) es:$(grep 'PRE' release.yaml | cut -d: -f2)"
                echo "La version $(grep 'PRO' release.yaml | cut -d: -f1) es:$(grep 'PRO' release.yaml | cut -d: -f2)"
            }
        }
    }
}