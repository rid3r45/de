def get_value(def a, def b) {
    return a*b
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