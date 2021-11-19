1. there is a brown cat on the page. it goes red when clicked or dragged, and I can drag the cat to move.
2. typescript supports modules but javascript does not.

3. Module bundler is required because: Browser does not support module system, although this is not entirely true nowadays. It helps you manage the dependency relationship of your code, it will load modules in dependency order for you. It helps you to load your assets in dependency order, image asset, css asset.
ParcelJS provides fast bundle times, zero config code splitting, hot module replacement with no configuration needed and automatic transforms using Babel, PostCSS, and PostHTML when needed

4. Value	State	Description
0	CONNECTING	Socket has been created. The connection is not yet open.
1	OPEN	The connection is open and ready to communicate.
2	CLOSING	The connection is in the process of closing.
3	CLOSED	The connection is closed or couldn't be opened.