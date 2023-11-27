

<div class="main">
    <nav class="navbar navbar-expand-lg p-3">
        <div class="container-fluid">
            <a class="navbar-brand" href="/">✈️</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="/">Accueil</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="/about">À propos du site</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <slot/>

    <!-- Footer -->
    <footer class="footer mt-3 py-4">
        <p class="text-light text-center">&copy; 2023 ulysseguillot.fr | Tous droits réservés.</p>
    </footer>
</div>

<style>
    .main{
        position: relative;
        min-height: 100vh;
        padding-bottom: 10em;
    }
    
    .navbar{
        background-color: #282238;
    }

    .nav-link, .navbar-brand{
        color: white;
    }

    .nav-link:hover, .navbar-brand:hover{
        color: blueviolet;
    }

    .footer{
        background-color: #282238;
        position: absolute;
        bottom: 0;
        width: 100%;
    }
</style>