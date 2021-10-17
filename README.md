function [m,n,z,q] = paulix_hadamard_2_social(userlist1,userlist2,type,diameter)

% social network user follow-back statistics

% use a scraper such as https://phantombuster.com/

% input two follow lists (or following/followers for same user) to find common users between follow lists

% input web-diameter variable to obtain a coarse measure of user relationship to web

% diameter = 0.35 + 2.06 * log(N)

% where N = # of webpages

% https://barabasi.com/f/65.pdf

% https://www.worldwidewebsize.com

% sample input:

% [m,n,z,q] = paulix_hadamard_2_social('kevin_following.csv','kevin_followers.csv',0,19);
