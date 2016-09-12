node {
  git url: 'https://github.com/Lazzaretti/pingwebsitemvn.git'
  def mvnHome = tool 'M3'
  env.PATH = "${mvnHome}/bin:${env.PATH}"
  sh 'mvn -B verify'
}