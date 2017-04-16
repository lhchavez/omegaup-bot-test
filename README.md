Este es un ejemplo de cómo usar `omegaup-bot`. La rama
[mirror](https://github.com/lhchavez/omegaup-bot-test/tree/mirror) fue creada
usando

    {
      "publishing": {
        "mode": "mirror",
        "repository": "ssh://git@github.com/lhchavez/omegaup-bot-test.git",
        "branch": "mirror"
      }
    }

mientras que el subdirectorio
[problems/sumas](https://github.com/lhchavez/omegaup-bot-test/tree/master/problems/sumas)
fue creado usando

    {
      "publishing": {
        "mode": "subdirectory",
        "repository": "ssh://git@github.com/lhchavez/omegaup-bot-test.git",
        "target": "problems/sumas"
      }
    }
