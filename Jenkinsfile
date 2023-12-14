node ("mac")
{
    stage ("Initialization") {
        checkout scm
    }
    
    stage ("Tests") {
        result = get_value(1, 2.0)
        println(result.doubleValue())
    }   
}

def get_value(a, b){
    println(a.getClass())
    return a*b
}