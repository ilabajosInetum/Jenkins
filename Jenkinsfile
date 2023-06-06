pipeline {
   agent any
   stages {
       stage('crear fichero y contenido') {
           steps {
               script {
                   def data = "Contenido del artista favorito" 
                   writeFile(file: 'c:/temp/ficheroNuevo.txt', text: data)
                   
               }
           }
       }
       
   }
}
