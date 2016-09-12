node {
  git url: 'https://github.com/Lazzaretti/PingWebsite.git'
  def mvnHome = tool 'M3'
  env.PATH = "${mvnHome}/bin:${env.PATH}"
  sh 'mvn -B verify'
}