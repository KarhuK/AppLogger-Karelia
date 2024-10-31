# AppLogger-Karelia konsolisovellus

Sovelluksen voi suorittaa konsolissa ajamalla komennon (App kansiossa): dotnet run 

Humanizer-kirjastoa käytetään tekemään Logger-luokan Log-metodin tulostamasta tekstistä ihmisläheisempi

Pääohjelma kutsuu Logger.Log(); eli lähettää merkkijonon Logger-luokan Log-metodille.

Logger-luokka (AppLogger.Logger):
Log-metodi vastaanottaa tekstin ja käyttää text.Humanize()-metodia.

Console.WriteLine tulostaa metodin tuottaneen tekstin konsoliin.
