# Songstats

Songstats provides music data analytics through its Enterprise API, enabling music industry professionals to access streaming statistics, audience data, chart positions, playlist placements, and catalog information for artists, tracks, record labels, and collaborators across major streaming platforms. Integrated with Radiostats for radio airplay data across 40,000+ stations.

**URL:** [https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/apis.yml)

## Tags

Analytics, Music, Streaming, Artists, Tracks, Labels

## APIs

### Songstats Enterprise API

Music data analytics API (v1) providing current stats, historic stats, audience details, catalog, activities, top playlists, and geographic location data for artists, tracks, labels, and collaborators. Authentication uses an API key header. Includes Radiostats radio airplay integration.

**Human URL:** [https://docs.songstats.com/](https://docs.songstats.com/)

#### Tags

Analytics, Music, Streaming, Artists, Tracks, Labels, Collaborators

#### Properties

- [Documentation](https://docs.songstats.com/)
- [Reference](https://docs.songstats.com/docs/api/e80265bb8b01b-songstats-api)
- [OpenAPI](openapi/songstats-openapi.yml)
- [JSON Schema - Artist](json-schema/songstats-artist-schema.json)
- [JSON Schema - Track](json-schema/songstats-track-schema.json)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [songstats-openapi.yml](openapi/songstats-openapi.yml) | Songstats Enterprise API v1 |

### JSON Schema

| File | Description |
|---|---|
| [songstats-artist-schema.json](json-schema/songstats-artist-schema.json) | Schema for Songstats artist objects |
| [songstats-track-schema.json](json-schema/songstats-track-schema.json) | Schema for Songstats track objects |

### JSON Structure

| File | Description |
|---|---|
| [songstats-artist-structure.json](json-structure/songstats-artist-structure.json) | Artist object structure documentation |

### JSON-LD

| File | Description |
|---|---|
| [songstats-context.jsonld](json-ld/songstats-context.jsonld) | JSON-LD context for Songstats entities |

### Examples

| File | Description |
|---|---|
| [songstats-get-artist-stats-example.json](examples/songstats-get-artist-stats-example.json) | Get artist current stats example |
| [songstats-get-track-historic-stats-example.json](examples/songstats-get-track-historic-stats-example.json) | Get track historical stats example |

### Spectral Rules

| File | Description |
|---|---|
| [songstats-rules.yml](rules/songstats-rules.yml) | Spectral ruleset for Songstats API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [shared/songstats.yaml](capabilities/shared/songstats.yaml) | Per-API capability definition for Songstats Enterprise API |

#### Workflow Capabilities

| File | Description | Tools |
|---|---|---|
| [music-analytics.yaml](capabilities/music-analytics.yaml) | Music industry analytics for A&R, label, and management teams | 13 tools |

### Vocabulary

| File | Description |
|---|---|
| [songstats-vocabulary.yml](vocabulary/songstats-vocabulary.yml) | Songstats music analytics vocabulary and domain terms |

## Common Properties

- [Portal](https://songstats.com/for/developers)
- [Documentation](https://docs.songstats.com/)
- [Website](https://songstats.com/)
- [GitHub](https://github.com/Songstats)
- [Blog](https://lab.songstats.com/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
