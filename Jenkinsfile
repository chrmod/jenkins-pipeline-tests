load('README.md')

node ("master"){ 
   stage("show groovy variables") {
      print binding.variables  
   }
      
   stage("show env variables") {
      sh 'env'
   }
}
