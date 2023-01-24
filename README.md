# Comp-9.8

public static void main(String[] args) {
        Math Calculus=new Math("Calculus", 1, "Moderate Math", "Math", "A", "Hall");
	History APWorld=new History("AP World", 1, "Hard History", "History", "AP", "Locke");
	English English=new English("English", 4, "Moderate English", "English", "A", "Petrushun");
        
        System.out.println(Calculus);
        Calculus.getTeacher();
        Calculus.getLevel();
        System.out.println("");
        
        System.out.println(APWorld);
        APWorld.getTeacher();
        APWorld.getLevel();
        System.out.println("");
        
        System.out.println(English);
        English.getTeacher();
        English.getLevel();
	}

}
    
