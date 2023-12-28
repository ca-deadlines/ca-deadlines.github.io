## CA Deadlines

Countdown timers to keep track of popular CA/HPC/EDA/NoC conference deadlines.

To keep things minimal, only top-tier conferences as per [conferenceranks.com][1] and personal preferences are listed.

This project is a fork of [ai-deadlines][2]. It is maintained by [Abhijit Das][3]

## Contribution

Contributions are very welcome!

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Optionally add `hindex` (refers to h5-index from [here](https://scholar.google.com/citations?view_op=top_venues&vq=eng))
- Example:
    ```yaml
    - title: BestConf
      year: 2022
      id: bestconf22  # title as lower case + last two digits of year
      full_name: Best Conference for Anything  # full conference name
      link: link-to-website.com
      deadline: YYYY-MM-DD HH:SS
      abstract_deadline: YYYY-MM-DD HH:SS
      timezone: Asia/Kolkata
      place: Kolkata, India
      date: Jan 01-05, 2024
      start: YYYY-MM-DD
      end: YYYY-MM-DD
      paperslink: link-to-full-paper-list.com
      pwclink: link-to-papers-with-code.com
      hindex: 100.0
      sub: CA
      note: Important
    ```
- Send a pull request

## License

This project is licensed under [MIT][4]. It uses [IcoMoon Icons](https://icomoon.io/#icons-icomoon): [GPL](http://www.gnu.org/licenses/gpl.html) / [CC BY4.0](http://creativecommons.org/licenses/by/4.0/)

[1]: http://www.conferenceranks.com/
[2]: https://github.com/paperswithcode/ai-deadlines
[3]: https://abhijitcse.github.io/
[4]: https://abhshkdz.mit-license.org/
