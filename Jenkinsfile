pipeline
{
    agent any
    stages
    {
        stage("Salto de linea")    
        {
            steps
            {
                script
                {
                    def contenido = "Este es un ejemplo con salto de linea \n"+
                            " y sigue aqui abajo"
                    println contenido
                }
               
            }
        }
        stage("Mover fichero")    
        {
            steps
            {
                script
                {
                    bat 'move "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\PPL_8\\Jenkinsfile" "C:\\"' 
                }
               
            }
        }
    }
}
