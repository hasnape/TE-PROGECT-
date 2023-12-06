<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Compte à rebours</title>
  <style>
    /* Styles pour centrer et formater le contenu */
    body {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: white; /* Couleur de fond initiale */
      transition: background-color 0.5s ease-in-out; /* Transition pour le changement de couleur de fond */
    }
    #countdown {
      font-size: 36px;
      text-align: center;
      margin-bottom: 20px;
    }
    button {
      font-size: 18px;
      padding: 10px 20px;
      margin-bottom: 10px;
    }
    /* Styles pour la barre de progression */
    progress[value] {
      appearance: none;
      -webkit-appearance: none;
      width: 100%;
      height: 30px;
    }
    progress[value]::-webkit-progress-bar {
      background-color: #eee;
      border-radius: 20px;
    }
    progress[value]::-webkit-progress-value {
      border-radius: 20px;
      transition: background-color 0.5s ease-in-out; /* Transition pour le changement de couleur de la jauge */
    }
  </style>
</head>
<body>
  <!-- Éléments HTML -->
  <div id="countdown">Cliquez sur Démarrer au début de votre appel</div>
  <progress id="progressBar" value="0" max="300"></progress>
  <button onclick="startCountdown()">Démarrer</button>
  <button onclick="restartCountdown()">Redémarrer</button>

  <script>
    let countdownInterval; // Déclaration de la variable pour l'intervalle

    function startCountdown() {
      clearInterval(countdownInterval); // Arrêt de l'intervalle s'il est déjà en cours
      let totalSeconds = 300; // Durée totale en secondes (5 minutes)
      let countdown = document.getElementById('countdown'); // Élément pour afficher le temps restant
      let progressBar = document.getElementById('progressBar'); // Élément pour la barre de progression
      let body = document.body; // Élément body pour changer la couleur de fond

      countdown.textContent = `${Math.floor(totalSeconds / 60)}:00`; // Affichage du temps initial

      // Interval pour mettre à jour le compte à rebours chaque seconde
      countdownInterval = setInterval(function() {
        let progressValue = (300 - totalSeconds) / 300 * 100; // Calcul de la valeur de la barre de progression
        progressBar.value = progressValue; // Mise à jour de la valeur de la barre de progression

        // Changement de couleur de fond de la page en fonction du temps écoulé
        if (totalSeconds >= 120) {
          body.style.backgroundColor = 'red'; // Changement de la couleur de fond en orange à partir de 2 minutes (120 secondes)
        } else if (totalSeconds >= 60) {
          body.style.backgroundColor = 'blue'; // Changement de la couleur de fond en bleu à partir de 3 minutes (180 secondes)
        }

        // Changement de couleur de la partie de la jauge en fonction du temps écoulé
        if (totalSeconds >= 180) {
          countdown.style.color = 'green';
          progressBar.style.backgroundColor = 'green'; // La partie restante de la jauge reste verte
        } else if (totalSeconds >= 120) {
          countdown.style.color = 'orange';
          progressBar.style.backgroundColor = 'orange'; // La partie restante de la jauge devient orange à partir de 2 minutes (120 secondes)
        } else if (totalSeconds >= 60) {
          countdown.style.color = 'red';
          progressBar.style.backgroundColor = 'red'; // La partie restante de la jauge devient rouge à partir de 3 minutes (180 secondes)
        }

        // Calcul des minutes et secondes restantes
        let minutes = Math.floor(totalSeconds / 60);
        let seconds = totalSeconds % 60;
        countdown.textContent = `${minutes}:${seconds < 10 ? '0' : ''}${seconds}`; // Affichage du temps restant

        // Fin du compte à rebours
        if (totalSeconds <= 0) {
          clearInterval(countdownInterval); // Arrêt de l'intervalle
          countdown.textContent = 'Terminé!'; // Affichage du message de fin
        } else {
          totalSeconds--; // Décrémentation du temps restant
        }
      }, 1000); // Interval de 1 seconde (1000 ms)
    }

    function restartCountdown() {
      clearInterval(countdownInterval); // Arrêt de l'intervalle s'il est en cours
      startCountdown(); // Redémarrage du compte à rebours
    }
  </script>
</body>
</html>
