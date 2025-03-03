 class ClassesAndObjects {

    class Movie {
         private String title;
         private int movieLengthInMinutes;
         private String rating;
         private String director;

         public Movie(String title, int movieLengthInMinutes, String rating, String director) {
             this.title = title;
             this.movieLengthInMinutes = movieLengthInMinutes;
             this.rating = rating;
             this.director = director;
         }

         public String getTitle() {
             return title;
         }

         public void setTitle(String title) {
             this.title = title;
         }

         public int getMovieLengthInMinutes() {
             return movieLengthInMinutes;
         }

         public void setMovieLengthInMinutes(int movieLengthInMinutes) {
             this.movieLengthInMinutes = movieLengthInMinutes;
         }

         public String getRating() {
             return rating;
         }

         public void setRating(String rating) {
             this.rating = rating;
         }

         public String getDirector() {
             return director;
         }

         public void setDirector(String director) {
             this.director = director;
         }

         public void displayMovieDetails() {
             System.out.println("Movie Title: " + title);
             System.out.println("Movie Length: " + movieLengthInMinutes + " minutes");
             System.out.println("Rating: " + rating);
             System.out.println("Director: " + director);
         }
     }

     // Main class
     public class Main {
         public static void main(String[] args) {
             Movie movie1 = new Movie("Inception", 148, "PG-13", "Christopher Nolan");
             Movie movie2 = new Movie("The Dark Knight", 152, "PG-13", "Christopher Nolan");
}
}
}
