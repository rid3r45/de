def get_value(int a, float b) {
        return a*b + c
}

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