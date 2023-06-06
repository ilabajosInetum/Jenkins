pipeline
{
    agent any
    stages
    {
        stage("Crear fichero de texto con contenido")    
        {
            steps
            {
                 script {
                     def newFile = new File("C:\\temp\\Ejercicio dia 2.txt")
                    newFile.write("Contenido de mi interprete favorito")
                 }
            }
        }
    }
}
