def get_value(int a, float b) {
        int c = 2
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