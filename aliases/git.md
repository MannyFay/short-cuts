# Git Terminal Aliases
## Working Tree
| Alias | Description |
|-------|-------------|
| `glc` | List Git commands. |
| `gs`  | Show status of working tree. |
| `gc <url>`  | Clone repository (add URL). |
| `gra` | Restore all changed files. |
| `grf <file>` | Restore a changed file (add file). |
| `gl`  | Show commit history. |

## Branching
| Alias | Description |
|-------|-------------|
| `gbsa` | Show all branches (inclusively remote repository). |
| `gbsl` | Show local branches. |
| `gbcl <branch>` | Checkout local branch. |
| `gbcr <remoteName/branchName>` | Checkout remote branch. |
| `gbcn <branch>` | Create new branch. |
| `gbdl <branch>` | Delete local branch. |
| `gbdr <remoteName/branchName>` | Delete remote branch. |

## Indexing
| Alias | Description |
|-------|-------------|
| `gisf <file>` | Stage file. |
| `gisp <file>` | Stage parts of file. |
| `gisa` | Stage all files. |
| `giuf` | Unstage file (add file or path). |
| `giup` | Unstage parts of file (add file). |
| `giua` | Unstage all files. |

## Committing
| Alias | Description |
|-------|-------------|
| `gci` | Initial commit. |
| `gcc` | Commit. |
| `gcm` | Commit with message. |
| `gcwip` | Commit with message 'Work In Progress'. |
| `gccl` | Change last commit (file/commit message) before push. |
| `gcrl` | Revert last commit (before push). |
| `gisacm` | Stage all files and commit with message. |
| `gisacwip` | Stage all files and commit with 'WIP'. |
| `gisacupdate` | Stage all files and commit with 'Update'. |

## Comparing
| Alias | Description |
|-------|-------------|
| `gdf` | Show differences between working tree and index. |
| `gitalizer` | Show differences between working tree and index (all files). |

## Fetching
| Alias | Description |
|-------|-------------|
| `gf` | Fetch actual branch from remote repository. |
| `gfo` | Fetch origin. |

## Pulling
| Alias | Description |
|-------|-------------|
| `gpm` | Pull from origin/main. |
| `gpd` | Pull from origin/develop. |
| `gpull` | Pull and fetch actual branch from remote repository. |

## Pushing
| Alias | Description |
|-------|-------------|
| `gpp` | Pull actual branch from remote repository, then push. |
| `gps` | Push actual branch to remote repository. |
| `gpr` | Revert last push (add commit hash). |
| `ggo` | Stage all files, commit with 'WIP' status and push. |

## Stashing
| Alias | Description |
|-------|-------------|
| `gsc` | Stash changes. |
| `gsp` | Pop stashed changes. |

