 //  Write the code to do the following
       
        // Loop through the array of films and check for the newest film
        
        // Produce one output to say the name of the newest film
        
        for (int a = 0; a < filmCollection.size(); a++) {
        
            if (year < filmCollection[a].year) {
            
                year = filmCollection[a].year;
                
                position = a;
            }
            
        }
        
        Console.WriteLine(filmCollection[position].title);
