# demo_git
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
	<h1>Candidature</h1>
	<form id="candidature" method="post" action="php_exo1.php">
		<div>
			<label for="nom">Nom : </label>
			<input type="text" id="nom" name="nom" 
				maxlength="15" pattern="[A-Za-z\' \-éèêëñ]{2,15}"
				placeholder="Entrez votre prénom" required />
		</div>
		<div>
			<label for="mois">Mois de naissance :</label> 
			<select id="mois" name="mois"></select>
		</div>
		<div>
			<label for="dispo">Disponibilité : </label> 
			<input type="date" id="dispo" name="dispo" 
				pattern="[0-9]{2}\/[0-9]{2}\/[0-9]{4}" />
		</div>
		<div>
			<label for="salaire">Salaire souhaité : </label> 
			<input type="number" id="salaire" name="salaire" min="15" max="50" step="5"/>
		</div>
		<div>
			<label>Collège : </label> 
			<input type="radio" id="employe" name="college" value="Employé" />
			<label for="employe">Employé</label>
			<input type="radio" id="cadre" name="college" value="Cadre" />
			<label for="cadre">Cadre</label> 
			<input type="radio" id="dirigeant" name="college" value="Dirigeant" />
			<label for="dirigeant">Dirigeant</label>
		</div>
		<div>
			<input type="submit" id="ok" />
			<input type="reset" id="annuler" />
		</div>
	</form>
	<script src="js/form.js"></script>
</body>
</html>
// modifier directement sur git
