# PrimeRinse

I built this website for some friends who are starting a local pressure washing business here in Houston. 

The site basically just shows off the services they offer (like driveway washing, sidewalk cleaning, and some add-ons) and gives people a way to easily request a free quote. The main goal was just to make something clean and simple that works well on phones and helps them look professional to homeowners in their neighborhood.

Built using plain HTML, CSS, and vanilla JavaScript.

For the "Get Quote" form, I integrated [Web3Forms](https://web3forms.com/) to handle submissions without needing a backend server. The form captures the user's data and sends it to the Web3Forms API using JavaScript's `fetch()` function, which then automatically emails the quote request straight to the business owner's email address.

Official website deployed on Vercel: https://prime-rinse.vercel.app/
