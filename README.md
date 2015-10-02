# Tax
Tax Versuche
sleep (0.5* 60);
hint "Der Steuereintreiber kommt dich in einer Stunde besuchen!";
steuer1 = (kblisfe_katbmcsha / 100) * 0.1;
steuer10 = (kblisfe_katbmcsha / 100) * 0.25;
steuer50 = (kblisfe_katbmcsha / 100) * 0.5;
steuer100 = (kblisfe_katbmcsha / 100) * 0.65;
switch (true) do{
case 1:
{
kblisfe_katbmcsha => 1000000
kblisfe_katbmcsha = kblisfe_katbmcsha - steuer1;
hint "Der Staat treibt die Steuer ein.Du zahlst ein betrag von %1",steuer1;
case 2:
{
kblisfe_katbmcsha => 1000000
kblisfe_katbmcsha = kblisfe_katbmcsha - steuer1;
hint "Der Staat treibt die Steuer ein.Du zahlst ein betrag von %1",steuer1;

}
case 3:
{
kblisfe_katbmcsha >= 10000000
kblisfe_katbmcsha = kblisfe_katbmcsha - steuer10;
hint "Der Staat treibt die Steuer ein.Du zahlst ein betrag von %1",steuer10;
};
case 4:
{
kblisfe_katbmcsha => 50000000
kblisfe_katbmcsha = kblisfe_katbmcsha - steuer50;
hint "Der Staat treibt die Steuer ein.Du zahlst ein Betrag von %1",steuer50;
};
case 5:
{
kblisfe_katbmcsha => 100000000
kblisfe_katbmcsha = kblisfe_katbmcsha - steuer100;
hint "Der Staat treibt die Steuer ein.Du zahlst ein Betrag von %1",steuer100;
};
}
