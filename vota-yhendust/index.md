---
layout: article
title: "Võta ühendust"
excerpt: "Palun täitke ankeet"
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---

<fieldset>
	<form>
		<p>Siin on tekst miks peaks meiega ühendust võtma</p>
		<label for="text_field">Nimi:</label>
		<input type="text" id="text_field" />
		<label for="text_field">Kontakt (email, telefon):</label>
		<input type="text" id="text_field" />    
		<label for="text_area">Lühidalt kirjelda pöördumise põhjust:</label>
		<textarea id="text_area"></textarea>
		<p>
			<label for="select_element">Pöördumise põhjus:</label>
			<select name="select_element">
					<option value="1">Soovin nõu</option>
					<option value="2">Soovin abi</option>
					<option value="3">Mingi muu põhjus</option>
				</optgroup>
			</select>
		</p>
		<p>
			<label for="radio_buttons">Pöördumise põhjus:</label>
			<label><input type="radio" class="radio" name="radio_button" value="radio_1" />Soovin nõu</label>
			<label><input type="radio" class="radio" name="radio_button" value="radio_2" />Soovin abi</label>
			<label><input type="radio" class="radio" name="radio_button" value="radio_3" />Mingi muu põhjus</label>
		</p>
		<p>
			<input class="btn" type="submit" value="Submit" />
      <label for="Submit">Saada</label>
		</p>
	</form>
</fieldset>
