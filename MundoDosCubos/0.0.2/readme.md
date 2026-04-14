# MdC versão 0.0.2

TBox obtida a partir dos slides 0330-OWL2-Axiomas-Propriedades.pptx.

Inclui os axiomas seguintes sobre as propriedades:
- inversas: estáSobre <-> estáSob
- temMassa: funcional (um objeto tem um valor único de massa em kg)
- transitiva: b -> estáSobre -> a -> estáSobre -> m, logo b -> estáSobre -> m
- simétrica: d <- estáAoLadoDe -> e
- assimétrica: c -> estáAFrenteDe -> g   (g não pode estar a frente de c)
- reflexiva: c -> temMesmaCor -> c
- irreflexiva: a -> estáAFrenteDe -> a  (não é possível se for irreflexiva)
- cadeia de propriedades: b -> estáSobreOCubo -> a -> estáSobreAMesa -> m então b estáNoNível2DaMesa m
