# The Superpower List Database

The Superpower List is a user-generated database of superpowers that was in operation at superpowerlist.com from 2008-2016. The database contains some 12,000+ superpowers, all of varying levels of sophistication, hilariousness, and creativity.  Each superpower in the database contains an overview, description, pros/cons of having that power, and keyword tags, along with some other meta information. The name of the user who originally submitted the superpower is also included.

Over the years I received many inquiries to provide a downloadable database of superpowers. Since the site is no longer in operation, I decided to put these 12,000+ superpowers up for anyone to use, free.

## Viewing The Database

Just download the CSV and open it in Excel.

## Using The Database

- All values are comma separated. 
- All string values are wrapped in double quotes.
- The first row is a header.

## Column Descriptions

- id: A unique integer ID for the superpower.
- name: The name of the superpower.
- overview: A brief overview of the superpower. This is designed the be prefixed with the phrase "The ability to"
- description: A longer, more detailed description of the superpower.
- pro1: An optional positive thing that can come from having this superpower.
- pro2: An optional positive thing that can come from having this superpower.
- pro3: An optional positive thing that can come from having this superpower.
- con1: An optional negative thing that can come from having this superpower.
- con2: An optional negative thing that can come from having this superpower.
- con3: An optional negative thing that can come from having this superpower.
- tags: A comma separated list of keywords relating to this superpower.
- user_id: The ID of the user who created the superpower.
- created_at: The date the superpower was created.
- updated_at: The date the superpower was last updated.
- state: All superpowers were reviewed before being publicly displayed. This field contains whether the superpower was submitted (needed review), published (approved), or rejected by a moderator.
- times_preferred: The old website had a "would you rather" feature that compared superpowers. This indicates the number of times the superpower "won" versus another superpower.
- times_rejected: The number of times the superpower "lost" versus another superpower.
- total_comparisons: The total number of times this superpower was compared to another superpower.
- preference_ratio: The ratio of wins to losses from comparing to other superpowers. This is a way to rank the most desirable superpowers.
- last_compared_at: The last time the superpower was compared to another one.
- username: The name of the user who created the superpower.

## License

While it's publicly available for your use, I still retain the intellectual property rights. As such, you have permission to use this database for personal or commercial use. All I ask is that if you use the contents of this database, simply put the attribution "Copyright © Justin Mahar | The Superpower List" in a visible location where the information is shown, with an optional link back to this project on GitHub.

Enjoy!

THE INFORMATION IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE INFORMATION OR THE USE OR OTHER DEALINGS IN THE INFORMATION.
