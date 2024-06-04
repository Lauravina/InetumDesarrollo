pipeline
{
  agent any
  stages
  {
    stage ("informacion de mi ciudad")
    {
      steps
      {
        script
        {
          Ciudad = "A Coruña"
          Habitantes = "250000"
          Clima = " soleado"
          println " mi ciudad es: " + Ciudad
          println " el numero de habitantes es: " + Habitantes
          println " el clima de hoy es: " + Clima
        }
      }
    }
    stage ("comando de tipo BAT")
    {
        steps
        {
        bat "ipconfig /flushdns"
        }
    }
    stage ("Nombre de usuario que ejecuto la tarea")
    {
        steps
        {
            echo "El nombre de usuario es: ${env.USERNAME}"
        }
    }
  }
}
    
          
