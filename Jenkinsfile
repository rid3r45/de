node ("rpi")
{
    stage ("Initialization") {
        checkout scm
    }
    
    stage ("Tests") {
        int a = 1
        float b = 3
        result = get_value(a, b)
        println(result.doubleValue())

        sh("""
        pwd
        which python3.11
        """)
    }   
}

def get_value(int a, float b){
    return a*b
}