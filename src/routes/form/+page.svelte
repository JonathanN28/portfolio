<div class='form-section'>
	<section>
		<h1 class="align-center" id="title">Riot Games' Feedback Survey</h1>
		<p class="align-center" id="description">Answer the questionnaire to enter a raffle of in-game currency valued at 50 USD.</p>
	</section>
	<section>
		<div class="form-container">
			<form id="survey-form">

				<fieldset>
					<label class="to-block" id="name-label">Full Name: <input class="to-block" id="name" name="name" type="text" placeholder="Full name like 'John Doe'" autocomplete="" required></label>
					<label class="to-block" id="email-label">Email: <input class="to-block" id="email" name="email" type="email" placeholder="Email with @ symbol like johndoe@gmail.com" required></label>
					<label class="to-block" id="number-label">I am <input id="number" name="age" type="number" min="5" max="150" placeholder="5-150" required> years old.</label>
				</fieldset>

				<fieldset>
					<label for="dropdown"> Choose your game for this survey:
						<select id="dropdown" name="game" required>
							<option value="" hidden="hidden">Games</option>
							<option value="FPS">Valorant</option>
							<option value="MOBA">League of Legends</option>
							<option value="Cards">Runeterra</option>
							<option value="RTS">Teamfight Tactics</option>
							<option value="Mobile">LoL: Wild Rift</option>
						</select>
					</label>
					<p>Do you find your chosen game the most fun or the most competitive?</p>
					<label for="1"><input id="1" name="opinion" value="fun" type="radio"> More fun</label>
					<label for="2"><input id="2" name="opinion" value="neutral" type="radio" required> Balanced</label>
					<label for="3"><input id="3" name="opinion" value="comp" type="radio"> More competitive</label>
				</fieldset>

				<fieldset>
					<p>How often do you play? (Select all that apply to you)</p>
					<label for="4"><input id="4" name="frequency" value="1d" type="checkbox"> Everyday</label>
					<label for="5"><input id="5" name="frequency" value="1w" type="checkbox"> Once a week</label>
					<label for="6"><input id="6" name="frequency" value="1m" type="checkbox"> Once a month</label>
					<hr>
					<label for="7"><input id="7" name="hours" value="2h" type="checkbox"> 0-2 Hours</label>
					<label for="8"><input id="8" name="hours" value="4h" type="checkbox"> 2-6 Hours</label>
					<label for="9"><input id="9" name="hours" value="6h" type="checkbox"> 6-12 Hours</label>
					<label for="10"><input id="10" name="hours" value="12h" type="checkbox"> 12+ Hours</label>
					<hr>
					<label for="11"><input id="11" name="days" value="1" type="checkbox"> Weekends</label>
					<label for="12"><input id="12" name="days" value="2" type="checkbox"> Weekdays</label>
				</fieldset>

				<fieldset>
					<label for="comments">Any other comments or issues? <textarea class="to-block" id="comments" name="comments" placeholder="I enjoy the games you co-developed with another group."></textarea></label>
				</fieldset>
				<input class="" id="submit" type="submit" value="Submit">
			</form>
		</div>
	</section>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
    /* Utility classes */
    .to-block {
        display: block;
    }
    /*.to-inline {
        display: inline;
    }*/

    /* Revert to original from Tailwind CSS default margin of 0 */
		/* blockquote, dl, dd, h1, h2, h3, h4, h5, h6, hr, figure, p, pre */
    hr, p, input, select {
        margin: revert;
    }
    /* Revert to original from Tailwind CSS default padding of 0 */
    fieldset {
				padding: revert;
		}
    /* Revert to original from Tailwind CSS default font-family and color */
		input, select, textarea {
				font-family: Arial, Helvetica, sans-serif;
		}
    ::placeholder {
				color: rgb(118, 118, 118);
		}

    .align-center {
        text-align: center;
    }


    /* CSS for the form */
    .form-section {
        background-color: #235789;
        font-size: 25px;
        color: #0C1115;
        background-image:
		url("https://images.unsplash.com/photo-1656464868371-602be27fd4c2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1064&q=80");
        background-repeat: no-repeat;
        background-size: 100%;
        background-blend-mode: overlay;
    }
    p, label {
        font-family: 'Hind Madurai', sans-serif;
    }
    section:first-child p {
        color: #F3F4F5;
        /* Suggestion by Linane to add more space between p and div's box-shadow */
        margin-bottom: 50px;
    }
    h1 {
        font-size: 3.5rem;
        font-family: 'Skranji', cursive;
        color: #F3F4F5;
    }
    /*h2 {
        font-size: 2.5rem;
        font-family: 'Skranji', cursive;
    }
    h3 {
        font-size: 1.5rem;
        font-family: 'Skranji', cursive;
    }*/


    hr {
        background-color: #F3F4F5;
        height: 0.25rem;
        border: 1px solid #F3F4F5;
        border-radius: 2px;
    }


    fieldset:first-child input[type=text], input[type=email] {
        margin-top: 10px;
        padding: 0.25em;
        width: 50%;
    }
    input[type=number] {
        vertical-align: middle;
        padding: 0.25em;
    }
    label[id=number-label], label[id=email-label] {
        margin-top: 10px;
    }


    input[type="checkbox"] {
        vertical-align: middle;
        width: 25px;
        height: 25px;
    }
    input[type="radio"] {
        vertical-align: middle;
        width: 25px;
        height: 25px;
    }


    textarea {
        margin-top: 10px;
        width: 100%;
        height: 100px;
        resize: none;
        font-size: 1em;
        padding: 0.25em;
    }




    .form-container {
        background-color: #EA3F45;
        /* border: 5px solid #EA3F45; */


        width: 64%;
        max-width: 2000px;
        min-width: 500px;
        min-height: 100px;
        margin: auto;
        padding: 20px;
        border: 10px outset #df4d4d;
        border-radius: 43px 23px 23px 41px;
        box-shadow: -96px -1px 4px 20px rgba(199,25,46,0.69);


    }


    input {
        height: 1.5em;
        font-size: 1em;
    }
    select {
        vertical-align: middle;
        height: 2rem;
        font-size: 1em;
    }


    fieldset {
        border: none;
        margin-bottom: 40px;
    }


    input[type=submit] {
        display: block;
        margin: 1em auto;
        height: 3rem;
        width: 50%;
        background-color: white;
        border: none;
    }
    input, textarea, select {
        border: none;
    }
</style>
