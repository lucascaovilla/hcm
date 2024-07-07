# HCM - Hydraulic Cylinder Maintance
<img alt="Static Badge" src="https://img.shields.io/badge/STATUS-UNDER%20DEVELOPMENT-darkgreen">

# ✔️ Techs:
- `Dotnet`
- `Angular`
- `Postgres`
- `Docker`

# :hammer: How to run

<h4>Run ´docker compose -f dev.docker-compose.yml up´ to start the application</h4>

<h4>Add to Program.cs to prevent https redirect:</h4>
<p>
builder.WebHost.ConfigureKestrel(options =>
{
    options.ListenAnyIP(5000);
});
</p>

<h4>Run ´docker compose -f dev.docker-compose.yml down --rmi all --remove-orphans´ to stop the application and destroy all docker artifacts</h4>
