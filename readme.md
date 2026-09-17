# Awesome Sports Betting Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Odds APIs, historical datasets, open-source tools, models, and communities for sports betting and prediction market data.

A curated index for people who work with sports betting data: modelers, developers, researchers, and students. The previous index of this space, ianalloway/awesome-sports-betting, was archived in July 2026; this list aims to keep a living, fair, and link-checked index for the category.

Every link on this list was verified live on 2026-08-27. Entries within each section are alphabetical. Vendors, including direct competitors of each other, are listed on equal footing with neutral one-line descriptions. See the Disclosure section for who maintains this list.

Betting involves real financial risk and most bettors lose money. If gambling is causing you or someone you know harm, free and confidential help exists: in the US, call or text 1-800-GAMBLER. More resources are in the Responsible Gambling section below.

## Contents

- [Odds and Line APIs](#odds-and-line-apis)
- [Historical Datasets](#historical-datasets)
- [Open Source Tools and Scanners](#open-source-tools-and-scanners)
- [Modeling Books and Courses](#modeling-books-and-courses)
	- [Books](#books)
	- [Courses and Conferences](#courses-and-conferences)
	- [Blogs and Video](#blogs-and-video)
- [Prediction Market APIs](#prediction-market-apis)
- [MCP Servers and AI Agent Tools](#mcp-servers-and-ai-agent-tools)
- [Communities](#communities)
- [Responsible Gambling](#responsible-gambling)
- [Disclosure](#disclosure)

## Odds and Line APIs

- [Betfair Exchange](https://betfair-datascientists.github.io/) - Official automation hub for the Betfair Exchange API, with tutorials, models, and data access guides.
- [Cloudbet API](https://www.cloudbet.com/api/) - Odds feed and betting API from a crypto sportsbook.
- [Genius Sports](https://developer.geniussports.com/) - Enterprise official league data and odds feeds, sales led.
- [LSports](https://www.lsports.eu/) - Enterprise pre-match and in-play odds feeds for operators.
- [Odds-API.io](https://odds-api.io/) - REST and WebSocket odds aggregator with value bet and arbitrage endpoints.
- [OddsBlaze](https://oddsblaze.com/) - Sportsbook odds API with pricing tiered by data latency.
- [OddsPapi](https://oddspapi.io/) - Odds aggregator with a free tier and flat per-request pricing.
- [OpticOdds](https://opticodds.com/) - Enterprise push odds feed built for trading desks and operators, sales led.
- [ParlayAPI](https://parlay-api.com/) - Odds and player props from 30+ sportsbooks plus Kalshi and Polymarket, with a free tier and the-odds-api compatible endpoints.
- [Pinnacle API](https://pinnacleapi.github.io/) - Documentation for Pinnacle's B2B betting API, a common reference for sharp lines.
- [SharpAPI](https://sharpapi.io/) - Streaming odds API with built-in EV and arbitrage detection.
- [Smarkets API](https://docs.smarkets.com/) - REST API for the Smarkets betting exchange.
- [Sportradar](https://developer.sportradar.com/) - Enterprise sports data provider with odds, probabilities, and official feeds.
- [SportsAPIs.dev](https://sportsapis.dev/) - Independent directory comparing sports and odds APIs.
- [SportsDataIO](https://sportsdata.io/) - Sports data and odds feeds aimed at media and enterprise products.
- [SportsGameOdds](https://sportsgameodds.com/) - Odds API priced per event rather than per market.
- [The Odds API](https://the-odds-api.com/) - Long-running self-serve odds API across many sports and bookmakers, with a free tier; the default in many tutorials.
- [TheRundown](https://therundown.io/) - Odds and scores API that also carries Kalshi and Polymarket markets.
- [Unabated API](https://unabated.com/odds-api/enterprise) - Low-latency odds API from the Unabated team, aimed at professional bettors.

## Historical Datasets

- [Beat the Bookie](https://www.kaggle.com/datasets/austro/beat-the-bookie-worldwide-football-dataset) - Kaggle dataset of roughly half a million football matches with closing odds from dozens of bookmakers.
- [Betfair Hub Data Listing](https://betfair-datascientists.github.io/data/dataListing/) - Historical Betfair Exchange pricing data, indexed on the official automation hub.
- [FiveThirtyEight Data](https://github.com/fivethirtyeight/data) - Archive of the datasets behind FiveThirtyEight's sports forecasts, including Elo ratings.
- [Football-Data.co.uk](https://www.football-data.co.uk/) - Free CSVs of historical football results and bookmaker odds going back decades.
- [Kaggle March Machine Learning Mania](https://www.kaggle.com/competitions/march-machine-learning-mania-2025) - Annual NCAA basketball prediction competition with rich historical tournament data.
- [Match Charting Project](https://github.com/JeffSackmann/tennis_MatchChartingProject) - Crowdsourced shot-by-shot tennis match data.
- [MoneyPuck](https://moneypuck.com/) - NHL win probabilities with downloadable shot-level data.
- [nflverse](https://github.com/nflverse/nflverse-data) - Automated data releases of NFL play-by-play, rosters, and more.
- [Odds Portal](https://www.oddsportal.com/) - Browsable archive of closing odds across many bookmakers and leagues.
- [Retrosheet](https://www.retrosheet.org/) - Play-by-play accounts of MLB games reaching back to the 19th century.
- [sports-odds-datasets](https://github.com/JacobiusMakes/sports-odds-datasets) - Open snapshots of sportsbook odds data, maintained by ParlayAPI.
- [SportsDataverse](https://www.sportsdataverse.org/) - Family of open-source sports data packages across R, Python, and Node.
- [Tennis Abstract](https://www.tennisabstract.com/) - Jeff Sackmann's tennis stats site with open match-level data.
- [Tennis-Data.co.uk](http://www.tennis-data.co.uk/) - Free CSVs of historical ATP and WTA results with bookmaker odds.

## Open Source Tools and Scanners

- [betfairlightweight](https://github.com/betcode-org/betfair) - Python client for the Betfair Exchange API.
- [betting-model-starter](https://github.com/JacobiusMakes/betting-model-starter) - Template repository for building a betting model against a live odds feed, maintained by ParlayAPI.
- [flumine](https://github.com/betcode-org/flumine) - Betting trading framework built on top of betfairlightweight.
- [implied](https://github.com/opisthokonta/implied) - R package implementing several methods for converting bookmaker odds into proper probabilities.
- [OddsHarvester](https://github.com/jordantete/OddsHarvester) - Scraper for collecting odds and results from OddsPortal.
- [oddsapiR](https://github.com/sportsdataverse/oddsapiR) - R wrapper for The Odds API, part of the SportsDataverse project.
- [parlayapi-arb-scanner](https://github.com/JacobiusMakes/parlayapi-arb-scanner) - Open-source arbitrage scanner built on ParlayAPI.
- [parlayapi-discord-bot](https://github.com/JacobiusMakes/parlayapi-discord-bot) - Self-hostable Discord bot serving live odds, line moves, and parlay math, maintained by ParlayAPI.
- [parlayapi-line-shopper](https://github.com/JacobiusMakes/parlayapi-line-shopper) - Command-line line shopping tool built on ParlayAPI.
- [parlayapi-odds-action](https://github.com/JacobiusMakes/parlayapi-odds-action) - GitHub Action that fetches sportsbook odds into JSON or CSV files from cron workflows, maintained by ParlayAPI.
- [penaltyblog](https://github.com/martineastwood/penaltyblog) - Python package with football modeling, team ratings, and odds utilities.
- [shin](https://github.com/mberk/shin) - Python implementation of Shin's method for computing implied probabilities from odds.
- [sports-betting](https://github.com/georgedouzas/sports-betting) - Python toolbox with betting datasets, backtesting, and value bet estimation.

## Modeling Books and Courses

### Books

- [Monte Carlo or Bust](https://www.amazon.com/Monte-Carlo-Bust-Simulations-Aspiring/dp/0857304852) - Joseph Buchdahl on using simple simulations to judge betting systems, tipsters, and your own results.
- [Sharp Sports Betting](https://www.amazon.com/Sharp-Sports-Betting-Stanford-Wong/dp/1944877541) - Stanford Wong's classic on the math of pointspreads, parlays, teasers, and props.
- [Squares and Sharps, Suckers and Sharks](https://www.amazon.com/Squares-Sharps-Suckers-Sharks-Psychology-ebook/dp/B01GSNQ876) - Joseph Buchdahl on the science, psychology, and philosophy of gambling markets.
- [Statistical Sports Models in Excel](https://www.amazon.com/Statistical-Sports-Models-Excel-Andrew/dp/1079013458) - Andrew Mack's hands-on modeling workbook, a common starting point for new modelers.
- [The Logic of Sports Betting](https://www.amazon.com/Logic-Sports-Betting-Ed-Miller/dp/1096805723) - Ed Miller and Matthew Davidow on how sportsbooks make lines and how sharp bettors respond.

### Courses and Conferences

- [Carnegie Mellon Sports Analytics Conference](https://www.stat.cmu.edu/cmsac/) - Academic conference on statistics in sport, with student research competitions.
- [MIT Sloan Sports Analytics Conference](https://www.sloansportsconference.com/) - The largest sports analytics conference, with openly published research papers.
- [Sports Performance Analytics Specialization](https://www.coursera.org/specializations/sports-analytics) - University of Michigan course series on building sports prediction models.

### Blogs and Video

- [Circles Off](https://www.youtube.com/@CirclesOffHQ) - Long-form interviews with professional bettors and betting industry figures.
- [Plus EV Analytics](https://plusevanalytics.wordpress.com/) - Blog applying statistical and actuarial methods to gambling propositions.- [Precix Blog](https://precix.fr/blog/) - French-language articles on sample size, bankroll staking, bookmaker margin, and closing line value, with free calculators.

## Prediction Market APIs

- [Kalshi API](https://docs.kalshi.com/) - REST and WebSocket documentation for the regulated US event exchange.
- [Manifold API](https://docs.manifold.markets/) - API for the play-money prediction market.
- [Metaculus API](https://www.metaculus.com/api/) - API for the forecasting platform's questions and community predictions.
- [Polymarket Docs](https://docs.polymarket.com/) - Developer documentation for Polymarket's CLOB and market data APIs.
- [PredictIt](https://www.predictit.org/) - Political prediction market with a public market data endpoint.
- [py-clob-client](https://github.com/Polymarket/py-clob-client) - Official Python client for the Polymarket CLOB.

## MCP Servers and AI Agent Tools

- [Front of Goal](https://frontofgoal.com/) - Soccer prediction market odds from Polymarket, exposed through a remote MCP server.
- [MCP Registry](https://registry.modelcontextprotocol.io/) - Official Model Context Protocol registry; search it for sports and odds servers.
- [odds-api-mcp-server](https://github.com/odds-api-io/odds-api-mcp-server) - MCP server for the Odds-API.io odds feed.
- [parlay-api-mcp](https://github.com/JacobiusMakes/parlay-api-mcp) - MCP server for ParlayAPI with live odds, props, arbitrage, and EV tools.
- [parlayapi-agent-tools](https://github.com/JacobiusMakes/parlayapi-agent-tools) - ParlayAPI odds tools packaged for LangChain, LlamaIndex, and raw OpenAI or Anthropic function calling.
- [parlayapi-betting-agent-starter](https://github.com/JacobiusMakes/parlayapi-betting-agent-starter) - Starter template for a betting agent: live odds in, no-vig fair lines out, one marked extension point for your model, runs keyless in Colab or Codespaces.
- [Pinnwire](https://pinnwire.com/) - Pinnacle odds, price drops, and no-vig fair prices over MCP.
- [PulseMCP](https://www.pulsemcp.com/) - Community directory of MCP servers, including sports betting ones.
- [SkipOdds](https://skipodds.com/) - De-vigged consensus win probabilities over a keyless remote MCP server.
- [VoxOdds](https://voxodds.com/) - Prediction market odds and EV checks over MCP.

## Communities

- [Covers Forum](https://www.covers.com/forum) - One of the largest mainstream sports betting forums.
- [r/algobetting](https://www.reddit.com/r/algobetting/) - Reddit home of quantitative and algorithmic betting; model builds, data sources, and API talk.
- [r/arbitragebetting](https://www.reddit.com/r/arbitragebetting/) - Arbitrage and low-risk betting strategy discussion.
- [r/CFBAnalysis](https://www.reddit.com/r/CFBAnalysis/) - College football data and modeling community.
- [r/PredictionMarkets](https://www.reddit.com/r/PredictionMarkets/) - Cross-platform prediction market discussion.
- [r/sportsanalytics](https://www.reddit.com/r/sportsanalytics/) - Projects and careers in sports analytics.
- [r/sportsbook](https://www.reddit.com/r/sportsbook/) - The largest sports betting subreddit.
- [SBR Forum](https://www.sportsbookreview.com/forum/) - Long-running betting forum, active since the late 1990s.
- [The Hive Index](https://thehiveindex.com/topics/sports-betting/) - Directory of sports betting communities, including Discord servers.
- [Unabated](https://unabated.com/) - Education-first betting community from professional bettors, with articles, a podcast, and Discord.

## Responsible Gambling

Most bettors lose money over time, and data or models do not change the house edge for the vast majority of people. If betting stops being fun, these organizations help, free and confidentially.

- [GambleAware](https://www.gambleaware.org/) - UK advice, self-help tools, and treatment referrals.
- [Gamblers Anonymous](https://gamblersanonymous.org/) - Twelve-step fellowship with meetings worldwide.
- [GamCare](https://www.gamcare.org.uk/) - UK charity operating the National Gambling Helpline.
- [Gambling Therapy](https://www.gamblingtherapy.org/) - Free international online support service.
- [GAMSTOP](https://www.gamstop.co.uk/) - Free UK self-exclusion scheme covering all licensed online operators.
- [National Council on Problem Gambling](https://www.ncpgambling.org/) - US organization behind the 1-800-GAMBLER helpline, chat, and treatment directory.
- [r/problemgambling](https://www.reddit.com/r/problemgambling/) - Peer support community for quitting gambling.
- [Responsible Gambling Council](https://responsiblegambling.org/) - Canadian nonprofit focused on preventing gambling harm.

## Disclosure

This list is maintained by [JacobiusMakes](https://github.com/JacobiusMakes), the founder of ParlayAPI, which appears in the Odds and Line APIs section above. To keep the list fair: ParlayAPI and its open-source repos are described in the same neutral one-line style as everyone else, competitors are included on equal footing with links to their own sites, and every entry is held to the same liveness check. Corrections and additions, including to competitor entries, are welcome; see [contributing.md](contributing.md).

---

Part of the [ParlayAPI](https://parlay-api.com) ecosystem: a real-time sports odds API with a free tier of 1,000 credits per month, no card required. Explore all the tools at [github.com/JacobiusMakes](https://github.com/JacobiusMakes).
