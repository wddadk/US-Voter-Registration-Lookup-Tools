# US Voter Registration Lookup Tools

A list of official state voter registration lookup portals, put together for name-based searches during Trace Labs Search Party CTFs (missing persons OSINT).

Each state's elections office runs some kind of "am I registered to vote" tool. Most of them can be used to confirm whether a name shows up on the rolls and in which jurisdiction. The catch is that states differ a lot in what they ask for. Some let you search by just a name; others lock you out unless you already know the person's driver's license number, SSN, or assigned voter ID.

The `Search type` column below tells you which is which:

- **Public** — you can get a result with info a stranger could plausibly have (name, or name + county / DOB / ZIP). These are the ones worth your time.
- **Self-lookup** — needs something only the voter would have (DL number, last-4 SSN, voter ID, or an exact address + DOB match). Skip unless you already have that data point.

## Quick start

Run the name through an aggregator first, then jump to the specific state tool to confirm and pull extra fields (precinct, party, voting history).

| Tool | URL |
|---|---|
| Vote.org — Am I Registered | https://verify.vote.org/ |
| VoteAmerica | https://www.voteamerica.org/am-i-registered-to-vote/ |
| NASS Can I Vote | https://www.nass.org/can-I-vote/voter-registration-status |
| VOTE411 (LWV) | https://www.vote411.org/check-registration |
| Vote.gov | https://vote.gov/ |

For deeper digging, **VoterRecords.com** mirrors a lot of the public voter file data and is searchable by name — handy when a state's official tool is locked down. Always confirm anything you find there against the official `.gov` source.

## States

| State | Tool | URL | Needs | Search type |
|---|---|---|---|---|
| Alabama | VoterView | https://myinfo.alabamavotes.gov/ | First, Last, DOB, County | Public |
| Alaska | Voter Information Lookup | https://myvoterportal.alaska.gov/ | First, Last, DOB | Public |
| Arizona | AZ SOS / county recorders | https://azsos.gov/elections/voters | Name + DOB (county-routed) | Public (mixed) |
| Arkansas | VoterView | https://www.voterview.ar-nova.org/ | First, Last, DOB or address | Public |
| California | My Voter Status | https://voterstatus.sos.ca.gov/ | Name, DOB + DL/ID or last-4 SSN | Self-lookup |
| Colorado | GoVoteColorado | https://www.coloradosos.gov/voter/pages/pub/olvr/findVoterReg.xhtml | First, Last, ZIP, DOB | Public |
| Connecticut | Voter Registration Lookup | https://portaldir.ct.gov/sots/LookUp.aspx | First, Last, DOB, town | Public |
| Delaware | VoterView | https://ivote.de.gov/VoterView | First, Last, DOB | Public |
| DC | Voter Registration Status | https://apps.dcboe.org/VRS | Last, DOB, ZIP | Public |
| Florida | Voter Information Lookup | https://registration.dos.fl.gov/ | First, Last, DOB | Public |
| Georgia | My Voter Page | https://mvp.sos.ga.gov/s/ | First initial, Last, County, DOB | Public |
| Hawaii | Online Voter Registration | https://olvr.hawaii.gov/ | DL/State ID + last-4 SSN | Self-lookup |
| Idaho | Voter Information Look-up | https://votertools.voteidaho.gov/ElectionLink/ElectionLink/VoterSearch.aspx | First, Last, DOB | Public |
| Illinois | Am I Registered | https://ova.elections.il.gov/RegistrationLookup.aspx | First, Last, DOB, ZIP, street no. | Public (address-assisted) |
| Indiana | Indiana Voter Portal | https://indianavoters.in.gov/ | First, Last, DOB, County | Public |
| Iowa | Am I Registered | https://sos.iowa.gov/amiregistered | First, Last, ZIP, house no. | Self-lookup |
| Kansas | VoterView | https://myvoteinfo.voteks.org/voterview/ | First, Last, DOB | Public |
| Kentucky | Voter Information Center | https://vrsws.sos.ky.gov/vic/ | First, Last, DOB, County | Public |
| Louisiana | Louisiana Voter Portal | https://voterportal.sos.la.gov/Home/VoterLogin | First, Last, DOB | Public |
| Maine | Voter Lookup (address only) | https://www.maine.gov/portal/government/edemocracy/voter_lookup.php | Address only | No name search |
| Maryland | Voter Lookup | https://voterservices.elections.maryland.gov/VoterSearch | First, Last, DOB, ZIP/County | Public |
| Massachusetts | Registration Status Search | https://www.sec.state.ma.us/voterregistrationsearch/ | First, Last, DOB, ZIP | Public |
| Michigan | Voter Information Center | https://mvic.sos.state.mi.us/Voter | First, Last, birth month/year, ZIP | Public |
| Minnesota | Find My Registration | https://mnvotes.sos.mn.gov/ | Name, DOB, address | Self-lookup |
| Mississippi | Y'all Vote | https://www.msegov.com/sos/voter_registration/AmIRegistered | First, Last, DOB | Public |
| Missouri | Voter Lookup | https://s1.sos.mo.gov/elections/voterlookup/ | First, Last, house no., street, DOB, County | Self-lookup |
| Montana | My Voter Page | https://app.mt.gov/voterinfo/ | First, Last, DOB, County | Public |
| Nebraska | VoterView | https://www.votercheck.necvr.ne.gov/VoterView | First, Last, DOB | Public |
| Nevada | Voter Registration Search | https://www.nvsos.gov/votersearch/ | Name + DOB or address | Public |
| New Hampshire | Voter Information Lookup | https://app.sos.nh.gov/ | Name + street/town | Self-lookup |
| New Jersey | Voter Registration Status | https://www.nj.gov/state/elections/voter-registration.shtml | First, Last, DOB, County | Public |
| New Mexico | Voter Information Portal | https://voterportal.servis.sos.state.nm.us/WhereToVote.aspx | First, Last, DOB, County | Public |
| New York | VoterLookUp | https://voterlookup.elections.ny.gov/ | Last, First, DOB, County, address | Self-lookup |
| North Carolina | Voter Search | https://vt.ncsbe.gov/reglkup/ | First + Last (DOB/county optional) | Public (most open) |
| North Dakota | No registration (polling place only) | https://vip.sos.nd.gov/ | Address | N/A — no registration |
| Ohio | Voter Search | https://voterlookup.ohiosos.gov/ | Name + DOB or address | Public |
| Oklahoma | OK Voter Portal | https://okvoterportal.okelections.gov/ | Name + DOB | Public |
| Oregon | My Vote | https://secure.sos.state.or.us/orestar/vr/showVoterSearch.do | Name + DOB | Public |
| Pennsylvania | Voter Registration Status | https://www.pavoterservices.pa.gov/pages/voterregistrationstatus.aspx | Name (or DL/PennDOT ID) | Public |
| Rhode Island | Voter Information Center | https://vote.sos.ri.gov/ | First, Last, DOB, city/ZIP | Public |
| South Carolina | MyscVOTES | https://vrems.scvotes.sc.gov/Voter/Login | First, Last, DOB, County | Public |
| South Dakota | Voter Information Portal | https://vip.sdsos.gov/VIPLogin.aspx | First, Last, DOB, County | Public |
| Tennessee | Voter Registration Lookup | https://tnmap.tn.gov/voterlookup/ | First, Last, DOB, County | Public |
| Texas | My Voter Portal | https://www.votetexas.gov/ | Name + County + DOB (or DL/VUID) | Public |
| Utah | Voter Search | https://votesearch.utah.gov/voter-search/search/search-by-voter/voter-info | First, Last, DOB, house no. | Self-lookup |
| Vermont | My Voter Page | https://mvp.vermont.gov/ | Name, DOB + VT ID or last-4 SSN | Self-lookup |
| Virginia | Citizen Portal | https://vote.elections.virginia.gov/VoterInformation/Lookup/status | Name + County + DOB + last-4 SSN | Self-lookup |
| Washington | VoteWA | https://voter.votewa.gov/ | Name + DOB | Public |
| West Virginia | GoVoteWV | https://apps.sos.wv.gov/Elections/voter/amiregisteredtovote | First, Last, DOB | Public |
| Wisconsin | MyVote Wisconsin | https://myvote.wi.gov/en-us/My-Voter-Info | Name | Public |
| Wyoming | Polling place locator only | https://sos.wyo.gov/elections/pollplace/default.aspx | Address | No name search |

## Bulk voter files

Several states publish or sell the whole voter file. This beats a single status check when you need address history, party, or voting record.

| State | What you get | Where |
|---|---|---|
| Ohio | Full county files, free download | https://www6.ohiosos.gov/ords/f?p=VOTERFTP:HOME |
| Washington | Statewide CSV extract, monthly (year of birth only) | https://www.sos.wa.gov/washington-voter-registration-database-extract |
| Michigan | Qualified Voter File, FOIA purchase | Michigan SOS FOIA request |
| North Carolina | Statewide data: name, address, party, race, gender, districts, history | https://vt.ncsbe.gov/reglkup/ |
| Florida | Monthly file: name, address, DOB, party | Florida Div. of Elections |
| Georgia | Purchasable statewide list | https://georgiasecretaryofstate.net/collections/voter-list-1 |
| Colorado | Bulk data purchase: name, address, party, birth year, history | Colorado SOS |

EAC keeps a national chart of what each state's file contains, pricing, and confidential fields: https://www.eac.gov/sites/default/files/voters/Available_Voter_File_Information.pdf

## Notes

- Most tools support either a name-based or an address-based search. The `Needs` column shows the name-based path where one exists.
- Confidential voters (ACP / domestic violence, law enforcement, judges) are suppressed from public tools in most states. A missing record is not proof someone isn't registered.
- New registrations can take 1–14 days to show up. "Inactive" status doesn't mean the person can't be found.
- North Dakota has no voter registration at all. Wyoming and Maine only do address-based polling/ballot lookups — use county or municipal clerks for those three.
- States tighten access periodically. If a tool that used to take name + DOB starts demanding a DL or SSN, treat it as self-lookup and fall back to the bulk file.
- URLs current as of 2026. A few (Texas, VoteWA, Vermont, Oregon OreStar) use redirect/login subdomains that can shift — start from the state's main elections site if a deep link breaks.
