# Comp-490-Proj-1

CGI program that reponds to the query string "csun" which will navigate the user to www.csun.edu

Experiencing 500 Server Error after running the cgi file at http://www.csun.edu/~ira14059/cgi-bin/simple.cgi?csun

Still experiencing server error, might be from wrong input commands in the ssh, but path and simple.cgi file look fine.

Removed echo "X-COMP-490: ${USER}" from simple.cgi file in hopes that might have been the cause but still recieving the server error.

Tried command chmod 775 simple.cgi in ssh. Still didnt work.

Fourth commit: Added .htaccess and index.html files

Got the server to Begin at http://www.csun.edu/~ira14059/cgi-bin/simple.cgi?csun but still not showing content.

Realized it had been put as "www.csun.com" instead of www.csun.edu" fml

http://www.csun.edu/~ira14059/cgi-bin/simple.cgi?index.html works but link to csun shows error
