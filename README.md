<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="Styles1.css">

    
</head>
    <body> 
        <!-- Netflix-like Navigation -->
     <nav>
        <div class="logo">NETFLIX</div>
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#">Series</a>
            <a href="#">Movies</a>
            <a href="#">My List</a>
        </div>
    </nav>
        <!-- Netflix-style Hero Section -->
    <div class="container">
        <div class="overlay"></div>
        <div class="content">
            <h1>How to Say Happy Birthday Before I Go Back to Melaka</h1>
            <p>This is how Amirul expresses love. In the meantime, you will understand how his brain works. See this,Amirul wants to say Happy Birthday to his Girlfriend.</p>
            <!-- Play Button -->
            <button class="btn btn-play">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-play-fill" viewBox="0 0 16 16">
                    <path d="M11.596 8.697l-6-4A.5.5 0 0 0 5 5v6a.5.5 0 0 0 .79.407l6-4a.5.5 0 0 0 0-.814z"/>
                </svg>
                Play
            </button>
             <!-- Info Button to open the modal -->
             <button class="btn btn-info" onclick="toggleModal()">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-info-circle-fill" viewBox="0 0 16 16">
                    <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm.93-12.412-.857-.03c-.686 0-1.178.465-1.178 1.17 0 .656.458 1.132 1.092 1.132.686 0 1.143-.454 1.143-1.13 0-.683-.457-1.142-1.13-1.142zm.436 8.416a.684.684 0 0 1-.68.66H7.5a.678.678 0 0 1-.675-.686l-.047-4.451c-.005-.338.268-.621.619-.621h1.12c.344 0 .626.276.626.621l-.047 4.477z"/>
                </svg>
                More Info
            </button>
        </div>
    </div>
 <!-- Modal structure -->
    <div id="modal" class="modal-overlay">
        <div class="modal">
            <div class="hidden context">
                <img src="sayang1.jpg" alt="Birthday Surprise Image">
                <p>On this special day, I want to celebrate the most amazing person in my life—my beautiful girlfriend.But i can't come there and celebrate with you today, So i create this to appre  You've filled my life with joy, laughter, and endless love. I’m beyond grateful for every moment we share. 
                    Happy Birthday, my love! May this year bring you as much happiness as you bring to me. Can't wait to make more unforgettable memories with you.</p>
            </div>
            <button class="close-modal" onclick="toggleModal()">Close</button>
        </div>
    </div>
  <script>
        function toggleModal() {
            const modal = document.getElementById('modal');
            if (modal.style.display === 'flex') {
                modal.style.display = 'none';  // Hide the modal
            } else {
                modal.style.display = 'flex';  // Show the modal
            }
        }
    </script>
        <!-- First Month -->
        <div class="row">
           <h2>Trending</h2> 
           <div class="row__posters">
            <img src="sayang2.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang3.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang4.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang5.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang6.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang7.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang8.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang9.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang10.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang11.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang12.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang13.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang14.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang15.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang16.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang17.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang18.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang19.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang20.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang21.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang22.jpg" alt="" class="row__poster row__posterLarge">
            <img src="sayang23.jpg" alt="" class="row__poster row__posterLarge">
           </div>
        </div>
        <!--Sec Month-->
        <div class="row">
            <h2>Selfies</h2> 
            <div class="row__posters">
                <img src="sayangselfie1.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie2.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie3.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie4.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie5.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie6.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie7.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie8.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie9.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie10.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie11.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie12.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie13.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie14.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie15.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie16.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie17.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie18.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie19.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie20.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie21.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie22.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie23.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie24.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie25.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie26.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie27.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie28.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie29.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie30.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie31.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie32.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie33.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie34.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie35.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie36.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie37.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie38.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie39.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie40.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie41.jpg" alt="" class="row__poster row__posterLarge">
                <img src="sayangselfie42.jpg" alt="" class="row__poster row__posterLarge">
            </div>
        </div>
      <!--Third Month-->
         <div class="row">
            <h2>Posing</h2> 
            <div class="row__posters">
                <img src="gambarsayang1.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang2.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang3.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang4.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang5.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang6.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang7.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang8.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang9.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang10.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang11.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang12.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang13.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang14.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang15.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang16.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang17.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang18.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang19.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang20.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang21.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang22.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang23.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang24.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang25.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang26.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang27.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang28.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang29.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang30.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang31.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang32.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang33.jpg" alt="" class="row__poster row__posterLarge">
                <img src="gambarsayang34.jpg" alt="" class="row__poster row__posterLarge">
                 </div>
         </div>
    </body>
<footer class="footer">
        <p>&copy; 2003 Your Mirmir </p>
    </footer>
</html>
    
         
