
pipeline [
agent any
stages (
stage('Clone Project') [
steps {
}
}
echo 'Cloning the project from Github'
git branch: "main", url: "https://github.com/ura-vf4/crypto-tax-calculator.git"
stage('Install Py Sonar') {
steps {
echo 'Install nysonar using pip'
sudo pip install pysonar --break-system-packages
}
}
stage('Scan the code with pysonar') {
steps {
echo 'Running PySonar... sh***
cd crypto-tax-calculator/
sudo pysonarsonar-host-url-http://http://13.49.238.0:9000-sonar-token-sqp_10ddac5a9b96c36fada4b03e0bd3cc8cdc6bf95a-sonar-project-key-DevSecOps_project_CI
