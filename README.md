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
class ClassesAndObjects{
        class Reel {

        private String userId;
        private int lengthInSeconds;
        private int numberOfLikes;
        private int numberOfShares;
        private String backgroundSong;

    public Reel(String userId, int lengthInSeconds, int numberOfLikes, int numberOfShares, String backgroundSong) {
            this.userId = userId;
            this.lengthInSeconds = lengthInSeconds;
            this.numberOfLikes = numberOfLikes;
            this.numberOfShares = numberOfShares;
            this.backgroundSong = backgroundSong;
        }

        public String getUserId() {
            return userId;
        }
        public String setUserId(String userId) {
            this.userId = userId;
            return userId;
        }
        public int getLengthInSeconds() {
            return lengthInSeconds;
        }
        public void setLengthInSeconds(int lengthInSeconds) {
            this.lengthInSeconds = lengthInSeconds;
        }

        public int getNumberOfLikes() {
            return numberOfLikes;
        }

        public void setNumberOfLikes(int numberOfLikes) {
            this.numberOfLikes = numberOfLikes;
        }

        public int getNumberOfShares() {
            return numberOfShares;
        }

        public void setNumberOfShares(int numberOfShares) {
            this.numberOfShares = numberOfShares;
        }

        public String getBackgroundSong() {
            return backgroundSong;
        }

        public void setBackgroundSong(String backgroundSong) {
            this.backgroundSong = backgroundSong;
        }

        // Method to display reel details (Optional but helpful for testing)
        public void displayReelDetails() {
            System.out.println("User ID: " + userId);
            System.out.println("Reel Length: " + lengthInSeconds + " seconds");
            System.out.println("Likes: " + numberOfLikes);
            System.out.println("Shares: " + numberOfShares);
            System.out.println("Background Song: " + backgroundSong);
        }
    }


    public class Main {
        public static void main(String[] args) {

            Reel reel1 = new Reel("user1", 30, 1500, 300, "Blinding Lights");
            Reel reel2 = new Reel("user2", 45, 500, 100, "Levitating");

            reel1.displayReelDetails();
            System.out.println();
            reel2.displayReelDetails();
        }
        }
    }
