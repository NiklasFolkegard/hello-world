# hello-world
Win: tömmer allt. Sparar. 
Tortoise Git > Add. Commit. OK.
Git Commit -> "master". Välj Commit & Push.

www: lägger till rad. Sparar.
www: Jag fattar inte hur jag ska få ändringarna till Win. Provade Tortoise > Fetch och Tortoise>Rebase. Det verkar funka.

Win: Tror jag har fattat nu. Skriver här. Sparar. Tortoise>Add. commit. ok. Git Commit > master. Commit & Push.
www: det kom fram. Sparar här. Provar Fetch & Rebase på Win härnäst.
Win: Det fungerade. Går direkt på Git Commit > master denna gång.
www: funkade bra. Provar git sync på Win härnäst.
Win: verkar som att Tortoise inte behövs?
www: ...för Tortoise är bara ett gui ovanpå själva git?

Win:
Nu har jag en förenklad arbetsgång där jag kan ändra och lägga upp/ladda hem.
Nästa test: Lägga till filer?

www:
Det gick bra. Har även lagt till desktop.github.com på Win så nu går det ännu smidigare att jobba.


Lin: Ändrat på Linux. git commit -m "lagt till fran Linux" git push -all

www: EDIT: på Linux använde jag git commit -a. Då öppnades en Vi-prompt där jag kunde skriva meddelandet, ESC, :wq och sedan gjordes commiten. Därefter git push -all

www: försökte lägga till filer från Linux, men körde in i ett antal problem:
1. Måste göra git -add *
2. Sedan git commit -a
3. Sedan git push -all
4. Men kolla först så att du har den senaste versionen från remote. Det hade inte jag. Då fick jag göra git pull URL först.


