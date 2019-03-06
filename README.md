# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
## Gem Used
# CarrierWave

This gem provides a simple and extremely flexible way to upload files from Ruby applications.
It works well with Rack based web applications, such as Ruby on Rails.


[How to render partials on specfic pages only](https://stackoverflow.com/questions/4637110/skip-before-filter-ignores-conditionals)

[![Build Status](https://travis-ci.org/carrierwaveuploader/carrierwave.svg?branch=master)](http://travis-ci.org/carrierwaveuploader/carrierwave)
[![Code Climate](https://codeclimate.com/github/carrierwaveuploader/carrierwave.svg)](https://codeclimate.com/github/carrierwaveuploader/carrierwave)
[![SemVer](https://api.dependabot.com/badges/compatibility_score?dependency-name=carrierwave&package-manager=bundler&version-scheme=semver)](https://dependabot.com/compatibility-score.html?dependency-name=carrierwave&package-manager=bundler&version-scheme=semver)

[How to render partials on specfic pages only](https://stackoverflow.com/questions/4637110/skip-before-filter-ignores-conditionals)

search filter
https://www.justinweiss.com/articles/search-and-filter-rails-models-without-bloating-your-controller/
<<<<<<< HEAD





<%= form_for @snippet do |f| %>

  <div class="field">
    <%= f.label :title %>
    <%= f.text_field :title %>
  </div>

  <div class="field">
    <%= f.label :content %>
    <%= f.text_area :content %>
  </div>

  <div class="field">
    add an image....
    <%= f.file_field :image %>
  </div>
end
=======
>>>>>>> 934e9bb4ec110fb889ad78ad20492a0087f9ca1f
  
  
  
import java.util.Scanner;
import java.util.Random;

public class Main {
    public static void main(String[] args) {
        //System.out.println("Hello world!");

        //Koala koala_one = new Koala();
		Ana koala_one = new Ana();
        Scanner scan = new Scanner(System.in);
        System.out.println("How does Ana scream?");
        String koala_sound = scan.nextLine();

        Random rand = new Random();
        int koala_intensity = rand.nextInt(100);

        String sound = koala_one.scream(koala_sound);
        int intensity = koala_one.intensity(koala_intensity);


        System.out.println("I am " + koala_one.getName() + ", I " + sound + " with intensity of " + intensity + " db");
    }

    public static class Animal{

        public String sound;
        public int loudness;
        

        public String scream(String sound){
            this.sound = sound;
            return sound;
        }

        public int intensity(int loudness){
            this.loudness = loudness;
            return loudness;
        }

        public String getName(){
            return "" + this.getClass().getSimpleName();
        }

    }

    public static class Koala extends Animal{
    }
	
	public static class Ana extends Animal{
		
	}
}
