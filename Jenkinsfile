node ("mac")
{
    stage ("Initialization") {
        checkout scm
    }
    
    stage ("Tests") {
        result = get_value(1, 2)
        println(result.doubleValue())
    }   
}

def get_value(int a, float b) {
        int c = 2
        return a*b + c
}