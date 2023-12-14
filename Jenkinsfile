node ("mac")
{
    stage ("Initialization") {
        checkout scm
    }
    
    stage ("Tests") {
        Int a = 1
        float b = 2
        result = get_value(a, b)
        println(result.doubleValue())
    }   
}

def get_value(int a, float b){
    return a*b
}