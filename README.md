# TemplatesDevOPS

WIP

Pendiente cambiar los secrets de AWS a rol segun secret.

Credenciales de AWS para solo el servicio interno, no para el github

role-to-assume: arn:aws:iam::519738254832:role/github_rol

role-session-name: sessionPruebaGit

aws-region: ${{ env.AWS_REGION }}

DEMO-> https://github.com/BatechIO/dumy_test/blob/base/.github/workflows/test.yml

