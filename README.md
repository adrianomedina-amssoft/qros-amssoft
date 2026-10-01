# QrOS — distribuição binária

Canal de distribuição da AMS Soft. A fonte própria da aplicação não é publicada
neste repositório. Releases contêm somente instalador, chave pública, manifesto,
assinatura e pacote versionado Debian12 amd64.

**Ainda sem release liberada para clientes.** O candidato1.0.7 é experimental e
está em validação de laboratório. Não usar em produção ou com dados reais.

Após aprovação, obtenha versão/hash do instalador/fingerprint da chave por
atendimento autenticado da AMS, independente deste download. Baixe install.sh
sem executar automaticamente, confira hash e só então use --verify-only e
instale com --domain SEU_DOMINIO. Domínio precisa apontar à VPS com TCP80/443;
SSH permanece na porta administrativa do operador. Banco e API ficam privados.

O cliente não precisa de acesso GitHub privado, Docker, Dokploy, Node ou compilador.
PostgreSQL18, Nginx e dependências nativas são provisionados por apt. Recursos,
backup externo e custódia operacional devem ser configurados pelo responsável.
MFA do administrador é obrigatório. Arquivos Web e scripts operacionais são
visíveis; executáveis podem ser analisados. Fontes/licenças de terceiros exigidas
por suas licenças acompanham o pacote; a fonte própria permanece privada.
