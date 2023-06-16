<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Kunconywa ukuthi ufake ama-nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) kuqala, bese `direnv allow` ngemva kokufaka uhla lwemibhalo ( [i-.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) izokwenziwa ngokuzenzakalelayo ngemva kokufaka uhla lwemibhalo).

Incazelo ithi: Ukuhumusha kwesiShayina kuya kusiJapane, isiKorea, isiNgisi, ukuhunyushwa kwesiNgisi kuzo zonke ezinye izilimi. Uma ufuna ukusekela isiShayina nesiNgisi kuphela, ungavele ubhale `zh: en` .

Incazelo ithi: Ukuhumusha kwesiShayina kuya kusiJapane, isiKorea, isiNgisi, ukuhunyushwa kwesiNgisi kuzo zonke ezinye izilimi. Uma ufuna ukusekela isiShayina nesiNgisi kuphela, ungavele ubhale `zh: en` .

* [ikhodi yangaphambili](https://github.com/xxai-art/web)
* [Amaphakethe olimi esayithi lilonke](https://github.com/xxai-art/web/tree/main/i18n)
* [Amaphakethe olimi amamojula okungena ngemvume](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Iwebhusayithi Yemibhalo Yezilimi Eziningi](https://github.com/xxai-doc)

Ulimi lohlelo lwangaphambili ngu- [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , olungeza izici ezithile ngokusekelwe ku-syntax ye-coffeescript, bona [./coffee_plus.md](./coffee_plus.md) .

## Ukwenziwa kwamanye amazwe kwamawebhusayithi kanye nemibhalo

Yakha kumaphrojekthi angu-3 alandelayo

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Isijobelelo sithi `.mdt` , ungasebenzisa i-syntax efana ne `<+ ./coffee_plus/import.js>` ukuze ubhekisele kumafayela angaphandle, futhi ukhiqize umaka phansi ngesijobelelo `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Ukuhumusha kwe-Markdown ngeke kuhumushe amakhodi nezixhumanisi, futhi kuzogcina imisho ehumushiwe. Uma ukuhumusha kuguqulwa kodwa umbhalo wangempela ungashintshwa, ukukusebenzisa futhi ngeke kususe ukuguqulwa kokuhumusha.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Amafayela olimi okuhumusha amawebhusayithi akhiqizwe yi `yaml` .

### Imiyalo yokuzenzakalela kwedokhumenti yokuhumusha

Bona ikhosombe lekhodi [xxai-art/doc](https://github.com/xxai-art/doc)

Kunconywa ukuthi ufake ama-nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) kuqala, bese `direnv allow` ngemva kokufaka uhla lwemibhalo ( [i-.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) izokwenziwa ngokuzenzakalelayo ngemva kokufaka uhla lwemibhalo).

Ukuze ngigweme isisekelo esikhulu sekhodi esihunyushelwe kumakhulu ezilimi, ngidale isisekelo sekhodi esihlukile solimi ngalunye futhi ngenza inhlangano yokugcina isisekelo sekhodi.

Ukusetha okuguquguqukayo kwemvelo `GITHUB_ACCESS_TOKEN` bese usebenzisa okuthi [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) kuzodala ngokuzenzakalelayo inqolobane yekhodi.

Yebo, ungaphinda ubeke kusisekelo sekhodi.

Isithenjwa sombhalo wokuhumusha [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Ikhodi yombhalo ihunyushwa kanje:

[i-bunx](https://bun.sh/docs/cli/bunx) ithatha indawo ye-npx, esheshayo. Impela, uma ungenayo ibhansi efakiwe, ungasebenzisa `npx` esikhundleni salokho.

`bunx mdt zh` yenza `.mdt` kuhlu lwemibhalo lwe-zh ngokuthi `.md` , bona amafayela axhunyiwe angu-2 ngezansi

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ikhodi ewumongo yokuhumusha (uma unama `nodejs` afakiwe kuphela, kodwa `bun` ne- `direnv` ayifakiwe, ungaphinda usebenzise `npx i18n` ukuze uhumushe).

Izohlaziya [i-i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , ukucushwa kwe- `i18n.yml` kulo mbhalo kungokulandelayo:

```
en:
zh: ja ko en
```

Incazelo ithi: Ukuhumusha kwesiShayina kuya kusiJapane, isiKorea, isiNgisi, ukuhunyushwa kwesiNgisi kuzo zonke ezinye izilimi. Uma ufuna ukusekela isiShayina nesiNgisi kuphela, ungavele ubhale `zh: en` .

Eyokugcina ithi [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , ekhipha okuqukethwe phakathi kwesihloko esikhulu nesihlokwana sokuqala `README.md` yolimi ngalunye ukuze kufakwe okufakiwe `README.md` . Ikhodi ilula kakhulu, ungazibheka ngokwakho.

I-Google API isetshenziselwa ukuhumusha kwamahhala. Uma ungakwazi ukufinyelela i-Google, sicela ulungiselele futhi usethe ummeleli, njengokuthi:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Isikripthi sokuhumusha sizokhiqiza inqolobane ehunyushiwe kuhla lwemibhalo `.i18n` , sicela usihlole ngesimo `git status` bese uyengeza endaweni yekhodi ukuze ugweme ukuhumusha okuphindaphindiwe.

Sicela usebenzise `bunx i18n` njalo uma ulungisa ukuhumusha ukuze ubuyekeze inqolobane.

Uma umbhalo wangempela nokuhumusha kuguqulwa ngesikhathi esifanayo, inqolobane izodideka, ngakho-ke uma ufuna ukulungisa, ungashintsha okukodwa kuphela, bese usebenzisa `bunx i18n` ukuze ubuyekeze inqolobane.
