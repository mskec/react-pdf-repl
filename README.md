# react-pdf-repl

REPL for `@react-pdf/renderer` with interactive debugger


## Examples

- [react context usage][context_example]
- [emojis 💅💅💅][emoji_example]
- [minPresenceAhead][presence_example]
- [test for dimensions][dimensions_example]
- [watermark][watermark_example]
- [react-pdf and tailwind][tailwind-example] with [react-pdf-tailwind](https://github.com/aanckar/react-pdf-tailwind) library
- [image fallback][image_fallback_example]
- [exif bug][exif_bug_example]



[Create new doc](https://react-pdf-repl.vercel.app/new)


[context_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgZRgTwDYFNkAstYwA0cAIhAMYCuIWAdsXAAoCGA5liQGrBYDuJACpYAHvAC-cAGZQIIOACIAAlCwsKMALRgAJlID0qujqyqoCgNwAoUJFiI4FVSxhYAwhAajGVAM7vPVzESN1xgDB0jEgoMTywAUWxaBjhJGTlFZw1LKysKT194QswsXzgAXhR0bDwCGAA6JzVXAAoEKzg4ACMIHTQALkQOzrgwFh0dYDo2QYBGAAYiYfEl8QBKazyC-EEWLuwPLzEKx2dXQ6CYNvXN_LpCuF39rBO2xzCIqLhfYAAvUtSawqAD44C1hgAeJ4HQLeepMWQAN2AJigcERLAwVCw5QQSB-_zK4nEwOGnQhPH432qOLx3WgqIAQhAYDA5HMSD0oKiAErANi4GBzVIkhAUD6RejiCH6Sl8Unk_TQgJHBoIiDI1Gkja5O4PHkQPivJDi8KSuiAkFDTp6-D4v4AySVPwqy4tZUXbw6zrAKRggCEBNKQJguFkRviUFkUBaCnGOm-DrKYFkYDgbMee2wjjkkDo9BgCm9cFUMCoUAt4JGcApvCNxWwuKQUmwIlIwFUGmAnkGCnDChFCuriFCZqM9RALDALVNn3oJBnEpIUxMIiB5SHw8csXziSwySus50JHt_0GQd8AG0V6IALqAskjNbiR8yuVDnXiW7bOBuLAYDBjXeMd50Tf5LQ3MFITlR8G1pdotzGCYphmRQAFY4AWBQli3FtREGAADeY4GIgASBAg3EABSAicOHLlUUECAwA5R9OgY0wABksCkIVMLozpiWGTca2EMRgTFCUjGlJVvCHN8621TZRDseATCkFgqAweAWnXUEqxrchqAPESIVYDgwJxBQAEEABYB2gXgGBcbs6HKBQMBYYxfAoKcsAHODcTg3x6h6PoSTYms5WpEomzgTF-ToABJVwQF8Xs8JETRChYWAB2JETqyhLMXgvXFLwANhIKq4AAJgADhIABmRY4Ba28Iq3IqDXlSKtwhP8AOBWYZUGjBCq6gb_3G2rRumib-rG4Emrmoa-uHKahts1bxvWoqlrQnaFpGGUeuO8kzr2k6lpG_Qlqu8kltmu75oemslpWl61q6jalu2r7dp-_b5sOgHzprfRLqBmsoeh975tu-64fhobnqRuHNvGgAJaaIDgPhoAiaRZHkFh0xKo63sx4F_vR6HqdBunJshw1wYhWH6ZuynkeptHXp5j7uYxpacYAvGCagIn0lJ8nniFzmQfl5mOcmlWfupxH-eF-a-e-7Whs-pn1b-pXjfm0XYnxwmE2l-LZewU2NpZ3r1aVEqJoU_hTP0cysHk_QjJoAslKsIA&modules=true

[emoji_example]: https://react-pdf-repl.vercel.app/cp_code=JYWwDg9gTgLgBAbzgMQgOxgGjgFQKYAeWcACgIYDme2AasHgO7YAiEAxgK4h4ZwC-cAGZQIIOACIAAlDxk2MALRgAJoID0MtMrwyo4gNwAoQ6gwA6GRWABnGDoCiICACtgAZQgcobPAAoEhnBwAEYcwAA22lAAXHBsENpwALwAfIFBcAAGABYwMGDW0WpqbMpoZs7W2uHAAG5QZmh4MGoU2WrW2RzKwGgUaoLhHDwwYQp4Tq4KHGjA8dpqZNbWzdZqACQI83hmMBAAMhAMOgDCS34AlHwA-gDMymZgfZmYhnwXRoaEkLBw2oJkDjheC-C7JFJwXzpAA8rE43AwaQycGh5CocGswAAXngkuIAIIANnESORKLojHSZIxMAAnuFcQgAtTkYJ0DA3Ni8LFboTXiyMtk8MA2jBYuIAIwABilAFJxPyBXBnBxbMBBLSTuyRuKfBgdAqqSyyDUKGgAJJ2ECFCR6ux6RXUvh8I1BUnU6H4IgpQC8G4AKvbgPsAlTuBkPB0OBv3QtRemDusmewhx8MpsNp0PR2Px5GJ72pwOAUl3CxHg5mk9mMrnk-mfUXayWg2Xva7K1n8-20024y2glXfQGOyWozHyy3oxSGPHo2i8KTo3CuCM0h9DEA&modules=true

[big_pdf_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgZRgTwDYFNkAstYwA0cAIhAMYCuIWAdsXACpYAejAasFgO4kAKAQwDmWOAF84AMygQQcAOQABKFkEUYAWjAATKQHpVdHVlVQFAKAsUIdAM7wdgmILgBeOAG0LcRD99wGIIOAHKCtABcigAywTAKRP6-UsBQoeFYUQoAYqkOCUlwwDBYIHZR3gEBCIVVNiZZAAwAzAAcACwFVVV0GVlMuKpiAML4WHZiAOKCUBjAFHAAQsB21MVwALLArF3dvgCO6FEAjIl7vmBQ85lwx62NjWfntnN0NzBQVFhPey_AbwBFI63H4BcSg3w1c5weo3BQtZoANl2e16kRiECoK2Agl6cEmNAARhBNtsUd1DmgThCApdrlEAEwPR61AJ_N5RD5fGm-dlYIFUkGs8GFAC6oJgEBcGAFjIlUsEGAA8nRXvzgQz5dKlVATFAAIIgTEMKJtB5PEWQwpBdLohSxfKglJpGBhO25F3k4qlcpeVlQ86wrLHB7Hck9PqKUaUCBBEpwUZUOgAawTEAgye4ZExwlw4YClOprIuVwoNwZTJZ0L5nM-32LcD5sqFe0t3QDeyDihDjWRPLgaLhAHVcN6E7gY3GxBt1IInCAcWmM1nyFRc_mDsDTg26WXGZX-zW4Fz69XVf91YLt62aR3ul2FMdEY1Ov3B1kthhU9GbFO0wA3UwsB0OAACVBGxewNzgQsW3OXdywPBsjxPQ9z0BLcaTbKo7zqCAGkUdpjmI6D30URYqBgEooGYCA4mAuAuCgYR_kXfg1DoSi7Gg2Dr3g0tEPNZD0PeOs0LVZs-KqbDqgbB8AFYQwZUjIwUdiKFxBMZgyDAEwwKgHFMbj-14_sEJOZ8q2eETa25YSJMw4Vbzk_C4URZpjgAThUu1jgZRsAC98X-UQoEJVQ5y04xsB4xzoXMuAGXkoSzzVWzT2shyryw5zoQfe5GjDN9VJ_WNnBGXAk1TABRHRgEJbAl0zMRV3XEy4v4-lEuSqzfhs48xPsi9JJy_0XII-EmVaHy4UWQRkwY_gFUlFBMTAUkdnawVNR3ASTgK8SL3Sw6MO20a9lwgIH0aTznxmrJhm02hdP1MAwEa0YCAmDSFo22Kzt2rrjnaFLMqOga7NS4aNXO9txrhRoAHYmXuxR-BoMBMzoOB-CzT7xiwH7pzJLai3ivbbhB3ruhQwaodOsnuhk8VCklaVJJ2qo2cVFUspOTmAm55VdVMQ1jRgRlmiQ3w2zvG1XVUh14idPIFfdVWvRKMoKjGvLXKyRTGmm4q7S2BgcfoYQsSg0m4L2BLgdBvq0ohjLneh7KnN1wN9cURSvNRhRhnTZq7DgXEQOGCL5GGKgwGMhtTMBvdbksk7RMhsGGbtsFcp9ibFKSwPSBmb8J1_cqAKAyOnqwDAw54YpcBQNQUEVZXE46-2Kcd6mqlpzP3ezqTc7FLVFWbZpx-VETJ-nnU9TFpMJbgdoqYtJ45biN04SV8lnVtOEPUdQpvW1v0Lvh4NGgZRHA8eqAdItjTsdKv9RmAdbg-XFqczzW2R5VAShWJ2NN-qoSGsPWGOEr6KGaA8V8DYyIKEmHQOQYgpDQGPPgOAAAJWMwAnBoDDkOR-YB_qM27kDA6kCM5uzAXzHOMtQQsy5gqGUMNWbsN5h7OUXDtQiwNEaZeUQqZWVltabeis4j71VjvLIx8O5VDPr6SocM9YTR7EVJBJVy5lXjImFMTUVx_woUw2kFMQF9zZOAumWdLyUNHpfDRcInwvkDp-Muk5K7B0AqoEC4FIIJ2hEncmXUrHp2OrQkaXtnH5zhIpRGiDoTIMenYfAPAtKP2enpAy1FgnnFCZ1FObjrG8lsYPBhvDzHM2nnPfhPNZ7Aing04Wi9hEmjgJZcRm9JGHyyHvFWLp5GKEUZrH0Os4mdl9goQ2zRi5UAwGWOAJg4DREJjgpUPB65mMARYoG69aFRPpg4mpedpkF2It5E2cJv6h3DsYBM0cExxwKXsIpVCSlpyOa7dOMSbzewuQk44ST77BAyVkp-wx9KGTSLssyPdvknOOfY_5TNzn3hmZWJE989HvwgH4xaqgYABTrm8ikXdugO0Oci350TKXMLHq05s7R55NMFKy1pC9RYdJXt0je_gt79JiDIoZwqcga1BCoyZ6j4nX0Kri7xBjKpGLuSYtc_9O6ezCSnCJPyIEnLRdJDFeFNEPHmTcrISpnC0EVGBCCdh_jGN_hq-FydBJlMbBU-h_d2WOMZVMzFZqkaByYFcd6FUlUjBDuqtqWr_X7N1dLexKKh6nL2TJK0LiDYguSecVJ4LeCQpydCvJRk3U6puKUyJdLDUMokCaq6Mz5LNGSoHdiuJKJLEotRJYag4UAIRQc0BvqXYGtRfWzNfhs2KEKjfDx2wGJMEWZ_MOmhbiNG7RgQk5KqiwRaZWxkzIa3jrTfUgFgbTUI1uo0MF2S65wFehG8cX1CbzWJpteN5iSzDs9QPH1NjGEZpYXU4Enk2WMPA1ywRS9OkguPf4CRVR5YjPtKKwoB81ZH0lafLWqjAVBtcaGRVFdlVVWddmV1tsBafI9SeuxZ7OEXtlUC-VfYdF2hHGON-lcZwaXnIuNVLq40hOaUOpNI7APg1PVU7OB70UEavVkeBIZA7IB4AQEoDhmCgDEBAKQ2CxAAE1-1wFIYIchg73X7Uk-UsdDHZPpugbJGdCgVPGw48Of4vbsjQHGPAAAUkSEk5nLNfr2T-kpNDaUydHdU4Dimm0TXgSjS1igZxY2EGZ7zpg4DZCuPQHQJCyEVuKVW6LKba0Tu1Qpy9SWEYeVvWlhQyBgAYD8SgMsDAw7gTsGAQkpgoBoAeSBDguI2tBCijoGK1HxPlgq2m1Njnmw0acSxwjTRW1Nc81kVr7XcvIC6zAMOyBW5bG0xHNZghALGBmGY1bQDLELcc0tuL2cHsNqZWw9mW5VtCx4cPP73CYO8sZIjJFn2s0BBQ9Ik-VRMOobGVKvDMqYGua0SR_RFVyNCcoyJwp9bIt0f1Q5t7TnYnraU92c1gdrUwFtbpQJjrX4xuE5q0TNXaP7ls16-zlSydGrW2juV1ObpqboPMBaup0zTejT_PH7OCec6pZY5Ni2quMeVwGyn9Wc0tAWUssQqz1kUE2ds3dBZCdwGpTz_9fzJ2Nt8ApEMHmUmqTNvAdidArb_At5uLXiaq00sq7FqTUCKfC9Y37Py8li6l3HFGqu_ji1krgI3GAzdTuuGQO3UrXPKa2-9fbgPU7LpO-bSAu9T8n3YD9zBK3DsIfq9D3Z-LzmodR8fKGZSzWeMGIJdXR9GAjTGDrx8lXv76P87D-T5jkeNuEXaAyY4FqduKAJCAEAw3Fj9rHw3nuwfm-k5n4L7X8-qcKDXsvvNqJVIhCwLYVaVAaIb4XGZ6AZQ88T5KYfl7GvlsO6Jbl4TQ3ytCu75qqTZBJhvC6SPS_RbCfoc4JpE4WSF584Aat7h5z4uYi6TRGyBxzQLQgRLQuArTIBrR_RWaHq3DPZk6vYn6AFVCsKCzsIcwQbxZA4CLtLixHoIba5CpYYDLobw5yKQE4bKIo4Xw67AFwjL7zrNav5tbzDACYjFYWZf6PbUJoHSbH6YGz61bSEwjNohir5u52ikCLLLLG4bJiBbI7JUFlYnC_50H_4C6MGGEKRbbtocRdoURUS5Y74zB74B4oEF5_pF70ol6O5GETTuQBzNZ-SBTBTe6mDhRqA1zRRYAaGB6Mg9RT4YG85t4R44Gd4FTaJmG3J4o-Iqo1R1QNRy7NQK7ZGhFJTaEciuEMFRFAExFwgFTsYVEfgbAABUcAtU9UH0rOTRDh-erR4R6BxeCapesC8IiksezWAWmIUAbww2-meWEEGeeW0ALEgEjE42GAk2gRr8EcM24Wc2uRbRdCCxZyX2LBP2goiM7B2cHx0G3BIilMEOSG0OUidogyGGoh6snoyOEyUh5-uuou5REBdofe2OqqkxrUiu7y--4Sauf-LehRWBBhsJMh8qaxa-AARBsAAGQbAtZTbcB2AjG47olknTHf7E4xa6H4n6HGrdEPg9j9GInDijjKqJ58ZzjhCCZommKsmaESZzE6HT56Gn6Q4eEzLEQeSBz4LbFgR0SGSjapAsQS6uAdqcTHbNHW6q4PH0FKnuFEk9HBhPg95r5Bx1xYDhTOAqHYwIHmnALOEz7WlcnKlLHo6IwkTNarj1FkCfxgAMTIlJ6LQ-Fmkyk5GJR-l6EBlNi2klEL4KBMjyQ37dDIJKgYAgTZDgqekJmdrwDID7BUAzDjA-mWnyntF4mZldF1bElwIPBOkDFRhjBpDHgkgZ5iD4JzBEJhxBYgDEg6nnH3Z3E0FWkdE2kAzYEd45nwK9hqYaaEDMARTHZepwAADSj8Ug8AoWjZWhzZjxkRix0RD4G54Bt-SJ4sQ244VwDgIAwQYEWAfijqkZkwwAp5ZmZCcAk505oEsYGAF5UWi5rZfqzxHZ9pXZqmzW6mmm_mOmtAjYBmw5cAJmMwwF6hyZoRdwsFnJbZt5vJMyKmApT5cIS0QQNEgRA5j-x5ggp50F5WZFipgZWZa5F-KW22vZCgGWIU2WDAuW-W3Ao-hFYWSB36Fpl5-RTxCWiFCkiIbaqFaCPAUgQQv0TATq6kmkD8UKMK-SnF9xV5GZ8FqlqpsRHk1yzpiREAQUAFKRYUEUGRsuFl3U3FBRFFCFdlsh5qtFhZuiievig-_AxKpK9htx1mYRylN5gVdpD4lYoZ7aEAYANgWxaeTcZA8ecZl2Jlz0PlDIaZXJ1lQG7e06uBV-K-gcr-2-u-PlvcSVda7ZQVWQ9VBZEYdo9-j-5Bz--INAb-Q4H-wRyBilP-flKlzmzBvgQsK21M_28FTI88IOPBq8zIPSgqfSghIqcOAQCOYhkJuG0JaiqVapz4vVAQyCniCepG0ahKASDqvuc5CVeqHJPFAVH2wZuBD598L5w2ow759OX5oEP5Rk4xUwgFZ5IFYFJIEFs5xF01XFVlS5vFnVV1yWhUPZgpD0gwKw4NYcn0FAyYahclSuU1DstB_pmNAVtlONcI7mgcQ4OWNEvmqg2miNslrVdN6ZDNNlNVZeSFsySk3hL8KesBZl5aqNjes1yVTN2ZF-iSt1vgBa6SRaJVD6pasKk1ClCtGNcF1VxR_FcJsyXhzWJpvhPaARLVtsnK1BbVJOP18FTthJKtFthUfkamyY2--kYg0QbWw266IYW6O6rVTeuJ5FwtZttVneN0d0vetcL0b0H0Yw3076lB8VztFVduStItyxN8-BzWhBi0y0JIQ1603p8tPcAtlVQtpt2BC1g5bxThnx6aHti1wOvxnSDIzQwegJvgMOIJwhx14J2GZ1EhF1VFwaCJdFhNEVNRFG6JZVOJLhJtRRq5CdOZ8kleKd96adEaBtEWaNqBxtsdzdnt5tnZl-S-wMgcA12MQ1L-o1wA7-UAn-ddk-rt_lcdLdoGgo8mPd2o8FIDbdPMm1fx-9oMw9gQwJu849yQk9Ci4hAQ0qMJXtd9y-KFzpoNxNn5YcGw0AEu3u2YppfNP9MFl9bt19PJal1FDwj5YVz5y8r5BDH5ENUNaQMNwUQFoWoFwWM5UFs2CVpFtD_9jCf1d5MySMqWzp6M4AWMOMeMmdb68BJMX6H2JF-dERHVfCgDzKwI8kndzYpjPxPKW1rQya8Do9SDR1KDwyp1jjRQkhl12DYtGOveVRZGqJ8ua91D7JIeV929N9u9F-_JbNwpkaT1mws4AmrgTJ0pudjhiUG99NW9BJDDXVyF-Ni9fZYNRDL65NlN_NitBjKVnj95JdHi80Yl7NElnNBWMl55QTNmkjc18dotzu-u4ZlhRuQdNhcAdhp985Lt31UjYTOTzNWQ7kDwgcrQLlyRoUaRkUj0mRZVfBITdD0zQu1TMy8zphBNigSzQUnDJNmwpQ0A9JU2teWzFT1WlFjD9ldwgcfkyz5dIENeYguMIw1xWR7TvlnThd3TyxlYiI6tA4uiwETgNExVqdG0OMWVOVdAZVej8xoLO9PTcjxE-TrDcIyA_tSwgdayIdcAYdm6FE26BtOj59qcjzmuhj4TOLIBU0BB76xBldT-NdWj8lZ9tNjLAB2NBzIBzQOKzW0QmI2IuIrgG-05tdqTMx2zR-uz2T-zrdS1W4EDq1QGOrvdVjfxSUG5Aqa59jQhrjJ1EJrjmDHjt9YtO1gcAAJEyBQx6bYA8yC5U8rfa9dOK6FX1bvNK46rKyNVOSSIq_y_OZWF6081U5q6wUxq8Y0tIxtX3SvGIqa7vea4dUohPc49a3m74La3PcCqXc6R7hbN7tbGM-IxiwqVM-q2fqKwjMyM666-QL0DAJ6Z6-1XGz6xE97cjEJSc2pBjCo38y-gTETDnVG3W0K24SKwm-3XAPq2A4wmu1A-m6IhVnY4gxa0W9IKg6Mug8W-46WzmvEfg6zmHMVc8rHPHFHQu50c8wEMuxPJSrq3s_9tA3BgCb0shvu7m7IgW1PTa-ey80RmLlpZLqYDoDLhMQEyk3O9QV9Ts429yRq0A44l--qz-9u-k3AwB0CeKqCSIaB2g9PRgxB7k13gqj48vTjlKVRkq2ydzrG0y1U762qQ8AG3dapFxiKXE2KYk6vch9TYbU2X25xwO6yyzd2bigQAOStLhaOYQoIMQkI-GyI-Uxx8K6-7M3k7ikU1-WTRTVQ6x7KejdJ_p1x4O3fYbCw4Gx-N5lWz7jbJZymRM-h109i8sS2ppYo4md2v4UxQ7Z57o8-8uQZ3AO-xwoKIiGY8CIl5Y0IltS7kR3tYB6R8g0exRye1R2e7PZB8GDdQul-I9VjvGa9UEuvVF1jTF9x7je4goWglhZgjRKpwQuORZyh2kxIzZ4u41_Z2LQFyOwU2pMF34b2sxbW3nfV4zUXa5nEU5_x75AyJ85y4-unb83jAC2VXkX_b5yy8sXEY5cJc5a5SFKkZ5Xc4CxF_S7MYNy-3Z3J1kH0R4sMaMXUYh40YEw98Aod5M8dzMy291Q_ccxN01X2kEa1fWy2aE02yqb4HF82N8d9im9Uuj8m20oa3Bu0Ca4hsRyPUB2hpa8exKoV248V7R24lC_dW1l4nE5Fcnkzu9UC2h6qxh0GbI81_T6pKgugtIFgl12ORp2U0CwN0d1iyd65ipvi854U4Q6Z_gKU71xJwK_XQtwA7L7gWN94VWSFzN-F31_nt51zyD_s0125B5KtxrapB80FF89t8-pOxs95Rz0Dz5zL6D9b-D9fk_Q_i_ZsWG2NRNR9fN3p0N4lEt7gfI-NwS1kEo5jIZWo6-jO5Gxr-M_D9ed6_Ndh3AK0El4KEX6l7BivCvp5Jl2a6T2R_m-KkjudefHayN3yaGQvYn4oBGY1KQNGbGb489VFYmXN2k-Vdr_Q1b638YX086RYYbiskM6brYebnD-P3s82379HuW8JZW17u5yP2bzn1Vev8j2D9HkXOGYVQP9V9LQ3PlVnm3BgIe3uliTNVHy97J6d7b-8xt071tz86o3-abNPea_JHv9U7z1VIenfFBKNWaqw9JeR_Juif3AE5kk6CfRXkHERYAD8YWdTRogSz7zt3-0XV7sXStrOk9sHWQ7PQH3IP9zs8AS7LEBuxwsyqDdAunn2KKo9gQpfDHjPEYTcCce3KNLn8WBiIxq-2bWvrlytZgdD2JbErt2DK7NYHqcZFngxDZ4edTebHQjkQIa4kCQyYZWfpiEjK983o_fCKgPmTw20kyAPSxIgKyaYcN-U_CaLg3QFrdKiJnYhqQzEqdsu0bTawUpWl7sC_OrmZfAyD47287QFEKQFIEVAhYAAkuQ2QC9Byas7Agah1sGI97Bp_Tfm5gU4-MlOYcFTjgjU49deayNURn4JobPdiBn_OXnjWM7K9Saqvczr4I0FWcOmVQnQTUL14x448UAJnlVxUE1wj6d_A4g_xzxP9V-2gxbmC2CG8dzuo7fUMPlsBFYRsz8XEKTURbBwtiLA0AZkJQEX5IBjVWATDwHQVCg8uwnnhe1nTDt2047VPhVHT7Z1M-mJEIvS3N4x01Wew3ngjHaD3BA4uQfzNngoIIFdyKhdFhcL4qOCEY7LMultxILOAq6wIvlhJzpaCspha1fPsYyvCbteB8WHEYIPL65Eh6xPBBjl3J75dKe4HGnoZ3FqgoU6WtTJDrRlplpThrQrztHU3oZDLhcg2ZAfXwZYCduB_TQdWgCH9tMRPAlbMX2ZagMt2ePFeFLDEECFUMdfJxg31PbU9m-Vwy2oF2EqWCje9teAWcKcIQiRW2QrRAr1cFL1me5ghiIsJHxFZJhHQ6YUYwlFJsZRuI97GmzlGMhd2JInNmT0PZSDKOVIzUTyJ7BQCMBdOBnPakghicWObIlohk0Fp2DuRtPB4PMIm6JDYO0ufCL91jQYkKUrw4BEmMbopjIRb3Lstv1HbBx2GINImlwx6w8M_yjUACgIwRrCMyhunJ0Tr195QimgvwlweEOwyAieWSLMNGCI57pDPhqYmkWgKrw5JsB6jDPsiJeE00D8Jo4bhWPhB4s_aAdL4GSwwCh0N0EdIUW0IZboiJ-zbTgQlylFdIvRQguDCKP4L7VlRkgino3xnqhi0xjQUkr2QpLUlaS7vekoyWY65gWSRorQd2MvFZC-xlY_nnaEF7tcReRQ7ruL3V6rjJO_g4Hj7yw5YjpRkDD0ack4KyiHxGbbZnuzJGBj3x6o2QbR0Ep1NMs4lHzC0xWEtDUh_XVgfozFEzDuhM_YSnPysKL8zccVBMW8KnHc8sy14_CbhyIn3jCRq7Wxn6IkHki1RVPWiTSKibNZBOsTKriJwlJJNQJBYl_kWKk6iiZOsfTvD2AzHQCsx5NODghwaL5i6uF45Ad8INh8jhKTIl3vczEbO0ORmTLkW6Mn5bjzRmOfFC9SHz2jTxXncSZbwcFbiIWYQ6FkiURZLRsqpDMqv5OTGBTTRsEnISvkHHJSbgFJViM6jDjd8dJ78UcDXTnBiB08zcXBEZHwBoAFAdgcCaJN9IbjdBcfNts1hdabpO27rNFhzxVYfCJJuUrcS0A6ChpBgBAKdhMHxAzA5gCwZYKsCxDwBnhhY_CWeKl7YTKmMjLUYVA1KKCgiuARULpCljLMAAqhLl_LFBhsAwUwEaFOxQATiy6KctgHMCS9RpnI6cZJIL7ERbxgMsvqDkSi9hFRL42HFRIpEfjqO1Is_nR1_EnN_xNJZAHSXGAgSkOGqdqexJmIli2B3EoIbgU0nOltJlXP8HpIXAGSsZ-ODCZr2xJdTlaUkmPlygxEgytqa8CGdlwOoBiQOqkkMfhjDE05msUYtQIzjeos4aZRky3CZIZkuSwBbk0XElOQRky4ylMyUlLOclQTXJLxd0ZKNZmpt2ZfxTmbtRr6US-ZPM2GUVy_EaSV8HfDAVqSwDDYIK9EfUsxFYjGlh-WssybZy6Gd5HOC6c2HvxraOifZ0fP2XvSuRA0f4t7R5FHDUAxxXkT7eWV8K1EfdFBX3MYpGWSbxjcZmgp7mHI_4WTUB6pQOIsLmA0BgouIT3M_mfSnZ7AQ0ilnAHkgnje2hc6oeKJx7mNbxFjHgQSNBmeRRBps8QebLFSWyaJNHWcasUDgbFn82pXYmWXypc1jiYgMbBLnOKuBLid3A7ozOLkX4fxeDYSrPK2JOzsKexfKtVDoA2Bn8IgMQEFnmDDYO0pubeSAJTkzjYuBfYiYRP1l9zf2K8HqMPKVFQyLZiOCefDLNHEYGOzPFejnNplbTMJcpbWQrK1E9g74zWccc-mUGGTvZe0wmbr0skKCK2jPcmT4htE1dmc0UxMbvJ4md4Ny8EuEIhIwTISRyqEzTmxLpnjNOJmLQIfgpzIrcf-m3Igt5N25ACPeEEgubgvMk0K-FDlH_kkTcqrNbu7vG4h1MsRe8LeOE-KcXWShIyJux8-eQZkXkHEd8cwKGmZhmDyB8EWFZRfd3kqoi1FXUg6UwQL78D3RAOU5K4oIn9z0uHQLmSRx5kqi8u_MmQZPIRkkzhKqs6_urOpl_dxOHCz6vjK4lSKiZlkx0vfFdLulu2j-TacZLXHhJYpmimCVuI3IWihxhNfIYOUMx4JWFE5DsZBQj4cTHFe8i2ilnoVZBcEFmMAMNnGq6gw4j-RYEEGSHsL4F9Myoe3M6HNKHOLuQOZ7ktghzfJ_XApftMmWjco5veG9qsPjnhAXkj7SXllNLE5TNx_nDydWIFEn1k5SC1OTyP17W0pudtMLoaLsXZ8ml0ii_IlPnEPo0pqLTKdQpSU5keqgfQaiH0UKf1v6EE94b9PGkxdmZK-IGfiL_n7hfRWXfxa-JUnjy1JoSiBXxNHaiy7UaguMXAtyUszUOiS7hXGycW092-xcQwT3z76Rxr-gwi2FWUoWPclleC3sVuMNilKipSfN9FcSPq5J9aFy8Zc6N4UX4yiYU6ouRizl5i2cO8t-eWPBYhVJV_eCKdFUICxUWVNuBVRNOWKHCFCxw2bqHMkW-yVl10EMPbMtFowLMpgHgDEzDjUtI6kvLhQ2zilFLi6pc5rOXOACVyAK1cnGLXMaj1y7Ajc9dC3MdVarLEP0gKX9KXYF8oMfc-CgmoEEIrbgiML3hRICVviYZYCm2WEsgX4MGVMC7BRz1JWurCl-wlpXUJ8buCSmzQkrM6t-ViqLaXKyWsZU2Gy1WRecnafsoJnJLm1ODXjoVJVkxMX0OgOFsi3SnbDS1TajlR6sHqBwbpwAO6egBGYGYmIhpQTNdkVDcAByj0r-hABeknFLpQUd6fUS-ngro12U2NdCoL69yBB8Fe9W4tTVgE_FJPUeWCRzUYrwFeUo6W0sUBLqV1w2JUOuoNIeytI_4HdUZGYD4AD1R6sQCeuYBEhPprVK9QcpvXdTE6089YpsQMXnyDiy85davLOIXEOIL87RtG3UVjSniFKlHgX3xHgM5JoM_lET2RXvqs1aK0Bd-rzXZDAa6y2sW-QaHfk7p_5OGrJS07gV6ljanVberwk5wZJgufDt6IXKALIZY9TjS4xCU_qQpCCNTGuAIqwLpZ_uPJYgpFU9jgpyxJSGgv5ECqjKr8ItZ_AJVGb68ss0zSavDlmrjCV7TyRsrvYJydlkaoGL2qSWmrXlLanoZfz6EkLVVg-JkSMMzytxxhz_GWSZvOEybMNe9E5RNy8k_NAtXyWdRZtcw3KguhvabgaK7XxLI-ly9-dkPj63DlG9w-aRow_TGrvePCuda5jnSWqyl1qmMlADtXegHViyJ1eCpdUI8MNEc_eZ6udLerfVOIIOYGrEDBrQ1zc1uSNIK1Xj41t45Nc-oI7HB5I_7NjaSI43Qzgl4yHjXlO8aFrGO_jWJbnMq2j8y142qFRlsiYPBdFnfFGYBIjjASnNOMh7XjI23uqitZA3UXctC4nC8taW6rf9Lk0MaN2TGravJCRVmyTtICzTedsFnfiPtivL7WjKAkYy_tM69LZNotpWaPlukOzdFoqiObDNOCtreysK0A1chhaipYUJYVi9NOpQqTaNqB2Vq76dCxqm1yYWdcUJnOiXhRvEZjbc-5KzzbjUPmjs0KhADCgZSwq7FcK-FGiMMqJWjLrOZm6CfzrFqs0tJHNQ4tzUCzCNtdKWhBXrvc1FywtAu2pidMYmNNmJ0lViQ2t50k65d8ncqpqU6XdLoAKw_pYMtTBW7jNNu9ofrp1k8iiI-g4SmVpohMBdSJQN2Zus9nMr6dGi9rUzv9kS1blUtLyXrXMp7K-dis8Wtiom4CTBmayYZqM1a3Z7GdWiordMsUGudg57PcFWyv7Udbuh3m6sb5rjn3sk5pe73Q7tG5ZboBOWwUQ0rN7BayVnHWjQjOK1g7St9yyHWYggY7Tu9tnLfcDtwISqoFAwlejKsclyrX5MO3Va5nTkVtM5P3M_VMXEVUbIVbqw3WlWVVH7wpUVGKmSgb3UaK15eiFsOoE6jrPo46gil8oynE7L9Ryzrb1OdL9S3WWS4aeIrQ19rQtfy_eTegp3CKmty4_AQDuFE76PNHAz-U-q8VrVyDSm0iaInaCHbUdqK07eioFmo4EZfG69gJoubFNIaImlsWJsEbc6UaXumA_GwBlAzEdwglHSPLR1jyuNLBrBtkNbUF721Aq4vXLXBXz7y1Oe5vXHztl1M0gZ084gpOum3Toaq6_dc9NMBvTkNpgVDWXsOkwjnSzveEWQSREEGRlnC-wzyJ9rcrkERLPcUHXJaUs1tGhrw7RwPk46rVCgfRafIXn7Fm4hGk4mvImybyyNNi-VSIdJ13050vh93IuhAjLo5g8cJueHQjWz785aBkLdHyX3Mzsebi-CnUa8WpqY8b647YwfR2FtMdrBrFd1p5V9kbt34EteIqe0y6e9uenMuGNpw2oxZMY5nE5qz3_7tD--2hbxy3KaZdyagfcqxRPLw0iKwh6Pcgp5HsGfNnB-sZcx4PQ1RNbYizBJqRo875Ke-kitLuP5yYfdymQqHbz6MKBXdklPzDzUt2e7VFWEhnWMZ0MrGFGO_epuQx-PNN3dEuoE2Mrt0dzx95q-QkQtYBLoV0xR4I2UfW1j7MD3tNoP-oUADAhgTWxabMHmBLAVgawDaSuI8NS6wjs4_1oHClZYgQ2eIeVhG3pM67o2lRhfRgYHUOtsDh9avDtzwNPCeT1u3XcaPxOe0YVX89xWwSNn90x-qm7me0dkMY6oSF2nTfR2u3QKmOms6AwcauW0c4ikRnrY-F_6CaGxVzI0AVg2HACn9TJj-XJsVNszf5BHdoEPKzZAL1NTBuQ1pt1OWaC1nkotUabu2ErpT0bEYy8bNOzj896JzE0UbXTHjcTqB108zI9OGyvTympfK0f9GBKgxBXeQy305UmEDcgk2vUvxGYr8EBrpxQ6DtHZ6jE9G-hs3KdB7Znbxip1NQyCkP-mHGgZ7U03yx0aSHg1m4ShgozpmDjTwxxs3lMLiWmvjJcKLVgoilxa8qowxLbng7OZHO5esoKQpqPMGsaDq7Q7aKAADc1gWwNpkuAQBhA2SdwLVSOLjYAoQ0qIHeGQSeAQg-oDYNVFFDkgwAE4dogoE8D8BcESoEIABd2AihxA15m8_YHgAThaAsgOQM-YDAlB1AsG1DMgAXAZ5dgj52qcGAKDwXEL2mAEFiFYBSgxAHgAABQABKdwAAD44AdF_wAAB5yA1AWgAwGYuFAOLQgUQHAEdSko3AZJbAKFzJKNgWmpBT0uJaCCj4NIMZaSw4EwBYA3ACATwGAFvmoB1LdgAAHTEgdAaAUUOIH4t7AOLqAKgCYAYCCDkAo1GYGgEam1SaI95oiyAE0vuXskkgFC6YHTCeWEAfltCyAEkD6ALL3QKyyFGwBWL_L6FpwC4E0sJXBAYViK1UEEu3yQgRIaDeFYEv6AhLWACKxxf0DcWaA1A_iwxYQs2AkLKAaK1gFishXnzdFpAMlYkBMW3ArFgMPoH0BHsn-uWTEPAB0uwBlCOl7rFuebhoINRdgfwNVbvMzBu2FAT-NXLsDs0M8sQvDM-eSsGWUgfVqAOxaqB0WhrC1pawwHausWjrI16uQZZUQGXsA3uA4pSUpLW55rl1hgP4EqtWBfAxKOeWxYEtcBeAaV6oBdcWujXjsq13AOtZ9AGXPyYAOi4dZesg3q5JAYAGdZG7fXcq-16EHAA4v_XMkC0NAJpeADmWGw6VpgIIHqIuW9QcAXK1jaBsI2TrMAa63hmhsWY4bZ8EgAACtUbotPYOjexiY3ab6V3GyJfQDYBNLngNS7XgMsuB6iEFHgGZbgD43NLAAAydYIAz4Bl2EOIGVvE3Bb5wDiywHYAk3BbktjS1peNt63TbhlnS-OpCj9g9bvgK2wZeBsM37bDtp25hmGB1wMAbt2m2ZYtvnBAbDt6oAAEIObAd2mwAH44AqthAC7dBu3XEG4IOAGrfjtXWpB2tiO1jayAKBxAWd9K_oENswAg7Dtg22wHgCm3xbTtm23VG9wkAnbZ8My8xfVtaxNbrkcQMVaLsl29bZd9gCLfUtV3Rb4wZ23OFrvCB67Q9wy4OCbst3SgBlwcB3cLvl3u7gt3uxXaHuD39LI9223Xf7tS2EITdxoJ3eXv52Aga9ve2bYluT3t7Y9ie1vcpAz2NblIRe13dPu-Bz7ldrS9XdHt22L7hlh-7reDvtgNbbZPO0A7PtL32AK92mx_Y3tf3r7Nd3-07aD1yjD7x9qB2_extF2L7m9_ez_d3tO21QTdgAPqkOyHpD9B8XcwewOB78Dre4g4IfX2iH5l8h-Q8ofQOsbNDsW3Q7wc73x7f926xeBIesOKHkDqh-A-Ku42OHVQD63rfEAMWwHq93G1nc_st9abTtmW9gDlu-3DCtNz8u7LoDJ6wAJwT1Ho5mCGlFgUoSUCAFNCmPzgU6aEP7b1vSOz72D1Rxo_JsxX0ipgL2-cTvt4PhriNhgE3fYdZ2uHl9jxxTe8dQBfHPtgR43fMuhPg74T3B8Pc0f1XonsT_x8PenuJOxHLj9-0XdPuqPMHkTrx65ayelOEHAkHR4hT1vEhBERjqavU5QdQAjHwcDANACyBoI3g0EPW_o8NJNPm5tT-CPg-EAcBTAC1xUFEHIPB2HHWNpxw7YKcBBk90ocoGE_ydhOin4Dkp-A8dvX30nlNnx97ZGdVAnblIU554xaeNOsqzTwWwM_-BDPZnQDhh-M8mfzBpnwzzB_M8ceKPnHp9uO_TYTtas0Afz1e5s-SfbOgHuzvZ2U4ycVOTnVT---gEuf2trneoIZ2fX6fmPHntzr53s9pBjOJngTz5887keXPFn_z8B4C8CcM3pb3CdlGC5gcQvS7UL4OzC52cHPPH8LvUJU4JfIO_5qLkbui9MCYuhXvgB54Y7xdkuHbrz4l1M4wAzOhXPz84JS8FvLPfAjQDZ6_chfl2cHPDtJ9y6OcxOTnAj5h8xaSesvy7xTuB2o5NtcuonCLvx0i6ltqghXPNwWyUHYCLDgAwgOgFkCuC5hktwdhpxi7xd2Pabob0V1lQ6ddPFAAAYiiFSA-n9znF1K-Mf4uCXz1vh_K4-eKvM34DlV3sDVe02LXLLnu2y_du2uXXhrx17y8Rf8umHF4d15g98BRu2n4b8V3AHbftPYwcbhQIm6iEpuzHBjp5127lfvONI-bmV7TaLfdAS3WNjVynZEfauT7Pd_QFI-NuSPuAPAFe7I6ZgKO8rm73wB9bIvkX4AZNut7lnouo3MbONnd_q7hfGvJAC4OgOqomBXysA-ofAHOE0vJRAHhT613sA5fdAn3mTht-cG_t8P-w392l6DZg_X3PbEH4Dw6_Kd6g5o5NR88aB0A0g1XJd6y7ZZgB5WdXrjoD6B-rfQgwPTrn2w2Cg-33aP199mwx63uHPonGH5MFh6TA4fWQeH1kJDZADEe13pHo2yh9od2uqP9b515R4QdjOEPW9wcHJ6lusfXL7Hzj8YFw9guS7pAcYBQHDTIHBPGD0m2R7OcUfIPqHnl8c6k9mf6Hsn5j_vZqd2fa3aH0wKp9kBceNPhQEu9FWuAGfxHwnoj6J-4fifzPxrvl9Z94f0fpPyLtAIp6c8WeoArn7Dx56qAl2BQvnwG2vdZAgeTPLHo1-B6s-Bfh7rz2L4Zb5AlfpbeXlT-oA49uf1PPHzT6yHcXpeBLlb_Z2J8c-GXlPknmj1F4i922OvBl1p-X3K9deXP1XtT9x-LcNe9gqzxUM16M8ifyP7X3r3F9C_IelvfXuuwN7dcDfRvCX8b7V8m_zvpv3QSGvADS8F2SPgHxbzl6C-7fKv3X8r8V-2_Nv7vV7_b5h8O_JeAgJd-_Od_QDzf_PWX0z4V868PfLPPX8L0V9s8rfDLO32H4nYcBhfQfFX974l_c_1fPPrIP74-hAABeIHJH7dwDYsAfXz3KAGADZeoH2XHLQ2Y101aQDeXwgJAYKwFbassXaqs1-AFhaX5QAd4z5ln3IGltqAeffPgAD6i_FACga819cIA_WBb2N4W5_ads_u9QkgFIBiZ0Al373Radxwc-KDYAm7DYNexw4I_UCRmgiFADT7QDG2EA3PnCxkDgCPWY7cAQACgEKd238L_t-0BtbTLgn0J4LvHvIriv210gEbg6AM83VRoAAFIEg0gbAKwEmCyAeAUQR4MeHLs-u_XAb317gHiASBDf0IY31u7ce2vCH5NuuE3cOwThYwcAEZJa-hBx3ZAHlwb8xDfNDT57GQX3-_fLeRWrv-t4v2J9L8DYMAFf03OmF0ixDSAUQOv-cAb8Pnskzf4QK3-QPO2QLWATv9je79d_A_W_ndxFdPdVXbznuTK9lYHI3v2fAYPm79YW_4_bvZtnS6ICytTlTAelqW-dN99GA9Qml5q89Yf8n-SAQsAqzDh5HFiwbBlbAq3d97_LAEf8BsKAEkBdiNWwADb5OwEztWwVkHV9gIQoBps4AffzJ9IAl_3GBnzfALwBNMTWz3IsAZq38BjLQUDvBJXFP1BBXnIZw0p6AsZ0scqIOQBmdqYV53wQrgAKFsBpQWx1BA1QRqWz8K-AywgZMEBgDLIFwQ8XaU64QCCmd94PgNaxSUKIGTU2wSAM_NCgQkAO9sPWNygAsgQd2TcnQeP175VADQE9IsgX8BoAUDKoB3U_XYOAkpOkBQF0o2ATQAcB5rWCyeBu2GAGwBNA-HD4ChwLABECogX0wwwlA4ABUDU4J0D4CpAkOlkD9sKZ00BLHEsk8D_Ab6GQM_AgIFoDqcMAFYA4ABPledr4XILBlcg_eHj9E_CAGT84INsGqsSgTpDvBCgxQFdZ4ERQIYBlAqtGHkVfEKEyDy8Tp30CE3TyEGDyQL1xgAw0dYQ64bHRQDjg-tDSAmBWgmAHaCTgEeEldMXamAkCYAWIJkDFARqQSCPnJINjAdAVIPkdrzTnz_tCAoe2IDCAUgM2NyAgMEaCGgsZyVdWNXwBV9TAHoLj82AUwMJgMgxQCT8gLFgKsd2AjdFBB23VgOsd8JSAEdQfghQHJs7AWMEohbFFggzd4EQQKwBTyAQOeCRLKgEJBjXd4JcDWAL4PMDbAAN0qDyQDmzyRAKNAAcC6gleFakdLMsE0ABsGAG3IbArILTcwQoEJDAs2bwN8Dd6dYMCDgguAFCD_AyQIlItghQB2D5AvYOSDDg6ILaCIgqtBS4qgMPwj9FAZ8Bj8s2e8x0AqADQDxCTA1IG-CLA34NJCs2IICH88QgIKCCg3EINAR1gzYMFAJQuQMIBpQg4NSDFqbl3eCVgzt0xC9vPUM-CDQokP9djQngHJBQQwEMmDlg9kPDCng7XD29YnC0IYABQ60KFDbQmILFCHQyUOdCNIfYJSDjAtgAqCqgkeDsC6AU7AwApALIHxDNAQrDdDjwcHw-8avbD3eDtAz710C-3foIHcpARoE7DOwmsPSc5bP0IJCAw6EL-DuQ7l3jDd6LgJuZeAhgFJdmAnN0ndPnPiDbAkPc4neDXndZHRD8g00LiBxwh4L4dQIQUOHk07BgH7Dd6HtzxcR4BgIvCjwoF2rl3glUNwBUCCUHT85gTP0UBsADijzCE_JPzoDMQs-HvDCEVUJBgvwgsN_CuYF8N9cgwhQA_C82NsDIg7wB8MRVnw711fCoImCLKD8wn8K3DMQ2CAQjAIx8O6hkImAAz8oIo7FsMQIrCOHkjwPCPD8CI4CNZgIIt8IUAyIi9XhxygyiM1CKYGiKAiVqRiLQi0QwMXYjKgsCJVIhvUGW4iCI58CIiSIrPyDd_g_cMFD71NsBdgJIjgIojhI7CPAiUIyCNkic_I4NJ9TgyAOgDn_Se3OD1LS4MZtdPG4IoDfAc6TXCIAKEKNCYQndHhCSgeYMWDgQrQOjDV2amBgiRIr60FCUQhiO0imIwNz0iBUY4KsA2ASAFgAF-aIUWRzvKixos4Aa8yAA&modules=true

[presence_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgFQKYA8YBo4AUCGA5qjgGrCoDuOAIhAMYCuIqAdvAL5wBmUEIcAEQABKKnz0YAWjAATbgHoxrWajFRBAbgBQ2-hFYBneAGF8UWXAC8cABRIAFuNVQc-9m04BKawD472nBwADzkVHDGAJ4ANqhWCEiUwLIwDgBccABMAAzZOGD4srLArIQZAKxwHBy-gUEhaJh19XAgJbhihmz0qACCToXxAMzlHM31UbHxCOMt3AYwAMrAAF6oGZkALFiz9QVFJYQAQhAwMPwVOy0tMBgwyFD4RvNQIBmCjGBgavT4XYJXa5BfTRaDvADEAA5oQDdtVxrUgQgBi4xi1ggpGjBEfVgliIjAYnEEjwFss1hkAIwANjcEFBUAhqEyzOZgiqNQQ7lu7A4GKxOIxYUotS8Om0GEgsDgqm4-EY0Xgth8Vn8tjqwToTBY7BxQWCBGIBKJ0zg-2KpQqHIiq2JAG0hrkcDlsgBdGq7UIUSi7IKTYkzIEtABWjGMwG4kRMC087x6Hg0gKDcHw0WAhFYAElbiBDHHPGpYcn4UC9ddgmYLL76ii1FZBE5oqC4ODKYJq8CY-x66RUNE4AA3emfGB_QfDsCjnMpmAAR0YqDg7i68_wMEYUDgaj4m9YEAARsBDAA6ODkUeL1AQQwy-nQVACcRQZitEqgfCntDge9b-Dzo9wKwwAOMA_YgPSqDhn8x7tsmCi1NWFbmJYtZQPWjbNuCmTstynj1l-UqXn-jAAUBIFgRBUEnuy8G6MmSFVsmQSoehfaYUMsFMbh3aCL2_ZDtEI5jgJQnTmu86LsuqCruum7btAgEHkep7nvgl7XreDIPlu5gvm0QEgB-nFArRQJCt6ZYYoaqCCgoWrMJ4oo6EAA&modules=true

[dimensions_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgFQKYA8YBo4AUCGA5qjgGrCoDuOAIhAMYCuIqAdvAL5wBmUEIcAEQABKKnz0YAWjAATbgHoxrWajFRBAbgBQ2-hFYBneMRgAhaKqhwAvHAAUAI0tqcwFRltwADAEpbAHzacHAAglBQ-ACeAHTAhuGRUU4uUP4A_HDOUFYx-DD27qroGZnZufn2fnAAXHCMHtzuqLI6egbGcBboXvZIYPiysu6EOCD4UITuOOWucIbAAF6ocBz-NgEOwXAAPORU2yGqjoyEh_MwUQA2qDYICOchA0MjWI9w45PT77NQAMIQK7QOqCADEqAATJDIYI3iF4VlUsgIGAAOrAWQwAAWdVMFhyahSBKgOD8cIRiOJACVgIQsTB0ZicXA8akiVYcABGXzkhG_CwwGD8RnY3Gocxs344CE8n6pAAyqG4DIxopZ4vxVnZcwAzLKKXBKKrmQtlukYgBtQTeQQAXTg6UynN58KxqFp9LqptQ5qtnLtDqdLo4HG2CiCvja-iM8CpEEovSQ9CxwCusmUq3Wm3s2z2FATxmut3uLPwYDqnO8OG4N3QNGAYkkwAMIL4lFhPFrqMi5bgAHJKD2-6sOEEEQhk6n02xQyEdgp9pQI1GOvAABLiKyJuCTtMZtaBLZztCYC5Fu5IGAYGDISJGbjQEAgxhgMBqej4QyoQQjgITlN7jO84njAy66BgkCwHAqjcPgjBXPA9hZkeux0EwLDsGO8I7AQxDzEstyCKEABsP6FjcF5wM8wysIQdQ6r-7w7BugxqAE1EjPOLFWFhCI7HGS7vHO3RUYMNGEDYgiVmRBF3BaACsVZwIptpcOGQm7CJHG0ZJELeHA0n4cscmKTgKlqbxFI7FpYkjJJOoAKQycZCAKUp5lwOpBrCRAPTaRJ1oGfpelwDqNpGcWblmd4qmeZZfE2S8OmCGFcAhZWPjOZFpnKTFFlMQoAnxbs3FsZ8UysFxm5sUxRUadZvkfBMFWSYZ3pyWFOBhbFXneQ1PTle4un6W1smuZ1QU9cVPkDc1Q0pU5EUdRCXUQlN9UiYNrCSSNwX6WFWVyZWXV5XFG2NVtO0-MpcBSPJh2ufJ8k4AALPJ60GvOdWfaVUABL8VWsX9tXxtNmmNb8R2ne1j3uadvWfSJkOuXpXJKajk1cDDUW5R93kIAoABUVHvmwMBECssgQKghisH28CGC-kFXrIcBumIcCEwos59UjqQdbF2M5R5CNWXzxJyUpx1pUp3VY2NOMi2D_WUlYR3PUFZmkoLCvC_DxVfaDTG_QEIDAOgLSAzxIOCd54OzV821Sfp4X-Vdo0uTjctnXbKuXYFhlu87mVLeNcN44jF1zU7jkh0H-nyYtQuy2t-W-5t0dXfJQUGfdolJQFnLZxl2fhdjE0vfr50Oy1gh3dd-l3T-QdFznpcPQpGtPet1eq2oUOkmj2tcPHQUd3rEdixD_OuVLSlz7FLcu-P4dp7z08S65laL7ZyX7Unuurz7689MjFpF0PynD_n4mtcXCch8n0WTwlG9q7PWua7nO8F5J7eh4rKuvd_YZXCmfOeg9MYAJyt7UWr8a7zV2j-M-0sIE-B1p7CaStgGZwWiHFB0ND6rRfthDOjss45yLsgme58NbSw1oQzBSlK4kJmk1chgVG7Zybn3KA6tL4MIwdlLu70158UKkbcRuFUBYXnGhZgZMwJAA&modules=true

[watermark_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbwFBzgFQKYA8YBoVwDKAbgOb6oAKAhjABYVwDijNpGjAasBgO6MARCAGMAriAwA7PAQAywSQGt8AXzgAzKBBBwARAAEoGasJgBaMABN1AeiOTLGI1F0BuJEmERJAZ3i9aJxBqKEUaejgAXgJdAFkANjgAJkSARjgAdjoAVgAbAGY4VML8s2K6eIKikrL8nNyzbKKATjozSrNS1KSzABYipIAJeIAtWPyM5Pi2_IaentTOoqXFpOSyunzqeOa4HbgABkPj3rLcxYuzJLbehvSe7LLqScmjo_TT7LoMqtTtveO72ScGyxHKjWInWoTSab2WJRmIxAPUKC2W6VWkOuT2K1UByzW6XyByaxNhgL6RTB52BhLG8TWGWIvUG2VSnCyqVSSLMzUaFTBzRpqTofxh-KBBxpvWoqSacvxi0KBxucyuZU6nCSYwy_RSDUeSs6Gvl7TgpUKhroMoAHHA7XCPiDpcQhvEmZ1RaksWrsbcyut7sRZvcislrecAxcQQTzUs_WMbZMUhycsHcvNA9Q7Q7jqGDsQ8hqRWcrkVqP1-nCDmX8mCS9kxqkDvd4qnQbNM104P1Q2tM6cnaHQeC26l_at1at0ckwdjspxx3d1Qs2qk7oHZ1y2o3YsU7SkZr6NXXOhmy6utvE7deJT2zpdVqqL30ni9Ffevj9Cf9Eo7zSCYJ1BCULio6SzAfkSIopu0aYlca6yoUuLgYSyQ2kcSQYRKlLeuufZFE22Som2WQdueaxdNm9ofmsBZFhcbRJHM5aVjhlH1juTYZP23pmJyuTxPxFQNHazZrg0lY8jCi4CkkXztEi3SHI0Zh2qU_S7N0bQZCMbgeF4vjwGA1DsIQwAAF4YFEPapM0AB0xHuIZfhwJYwCuZEPYHO42CQLAbkYOo1CiLk8AABQAJRRAAfHA4UEAAPEIYgSNIMUEKgiVsNZPiWRgkS6AAgvEugZagFVwIl3B8JllVwH4ACeuQFQgyD1fVdAYMApB0DAABcejNgcACkuiMB1qAAFaiH4wDqI1ADC3gwFIA16MIa1OONdUddQuQ9ZIACSq0gD4g26Jt0jbRNk2kNQYCDUkBy3ZVKgqLtcDlZNiWYDgMWDBguS5BAcC8NAuSWHAhmrdIiU2H9MAZZ9WXyEocB0EY6iFX1MBgOdNg2KQwD0KIABG9leCANjuRgpDaKIUDUHYximBY1g0x5Yg-Hl3g-DYSSpPE2RlSjFVoIMR2EHAUtwLIR0AHIANJi_DaOKN9lXwzVvDIx11U8LwGjAFgGBQ01LWRG1cCQHlMDAN4F3UGTPgQLkoirbocDvZr9WJSQpBg8Alj0IVSTNBk9nxL0XtdT1fVWyZZn5Wo6jAMDhWSN4GCi5NFUIEVUBM419maNoCV55VCBwC1kikPQg2xLQdD2VoogOOFScYOZVlwDYbkeTA0UANQASor2TeFAD6uBwMA0WRHFwBi6gkX2cEYDheFigYI1C9xRXldZUwK_1TvjVW-fH1H5VMBM746jQCAVsAAZaDAgThWUSTRXf1C-LkT-ZgAAkCBz5wAAFRFF6CoMAWBZ6gNPh1cBUD3J-CQRVWBWBIov2vjfX2R9srNzclbAIq0oDBFCOEOgqd065EKgAYgOMwr2EATLCBJhfBABx7L5GyGoGwBDK6JSYHAP-D8n6FXET4QBq0AAa4VnoHDgZFXON8tbUJIQgMhQQQhhGbrQjOugmEsLgGwkwnCrY8L4QIoRed4ZMDsX7GwjjT6RUing_WNgA5CO1obX28McrfXhilcQa0MqRXcEAA&modules=true

[tailwind-example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgEQgYwK4gKYDsYA0cACgIYDm2RAKtgB6FwBqw2A7nAL5wBmUEIOACIAAlGyk0MALRgAJjwD043HOzioQgNwAoUJFiI4acaRjZqHbnwHDTU2QukxSwADZtgq7Tp1oIuADO8DAcALzGpuaWABQIOnBwMAAW2DgAXIgJiXD05qqZ8Tk5_m7QgYXZxYmYwQKZQv5QuDxlbOoARm4Y2EIEVTmc_cVD2aOcAJS6OvQG8Go8pBhu8DwYuFLAAXAAgmBgMRNZieIwGM1wMQMAPKiYOPgAfAOJ12SUcIHAAF7YYUI7AAsQk-MAAnm4_ghQjEhGBpIDeJC6Ej6NJ-BxWmi2FBSGA4OQ8QihBNOM9qjkEABtAB0dJ2UFxYJiAEYAEwTAC6NJAeJiMQA-kRgEcwo9Li9qtcWOxJRSANbYMFhBDAThy6rBCFQmFCLF0aQsuAgLzSNjSKlsgAMVrAME5cHhiP10lKcA65GkXR6hptJPVFIpOLxKsWbkC2ADgcS5OjOWutAYoO1Kt15gY0jZdDcvACMg6EDcciSeVdGDqIH9sbjOQAythNttVXAANRwFlRmvXRSJmDVuMJvLJyGptiw9MyQKV0n9msAGWgaTgwDAgSwcDkhegn2A8FIOEY_iCDfMZygcFIchXwECaC85Fybl3NLgADllm5SBqKRHwOpcjwPDAHeZ5wE-HTqBAy64GBpCLtgMAvvWxbAJIyw3kQvLkLgpCfOWd5gLu37VGAn5oOoZjGAIIAQJuRBQDe5ZJOchGBEkXh3nI6zwE-5DLKQRCSLkGA3jRxYAFbljAEDEcUv7LsWDFroEL7vm4n6CNgIlTrRcAAG7YMEwAdMs66QhAmGFk-bG8nQoBMYEeKsLgsk5N0UhMV4L4sHp-5MbykJrpeuF6csYAYC45hwNAOHiC-ACySxKXAEUXmg9yOS5NbFDw2DWd5wC-SATF4KAKXNAJKUrAx5FsVpuT8GxkhEB0xl4FxggGckwH8a5iSQSpJC4oZeDwCua6CNAd6WYFMCsASuJ6cAci4TASlzQAjj0F6MCthEmYEfX6bupDYLkwQvsQySkBG6lMZCHlsbgH6VUeEZbZR9UmiljDmOA5ZHeFbhLbFcC4NgW3YDSrndr2s5SooMpsPDiQTKSkrdu82D9t2dxYKNsZTDo6pAA&modules=true

[image_fallback_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbwFBzgMQgOxgGhXAZRgE8AbAUwIAtzzd8ARCAYwFcRzs9UAFAQwDm5bnABqwcgHcRASRCDh-ACrkAHvQC-cAGZQIIOACIAAlHJ9mMALRgAJtoD0ZzLfJmohgNxIkGbADozAWAAZxg3AApkVG0-EGBSYgAuIwB5EMk-UltDERCoZhTDKhgYMBCkhwdtLBgQ_wEwvhhgZn9mfQcQhwgMrNsHADcARgBmBwBNAH0lAGlRADYIAA4AdQhBgCMAVVtRkCmADQBOPgBBM_9S7VykDQBKbyQOzDC4MLJyELgAXkISCjUWgwdpmZrkKL4TYQWzJRD4VBgPi2WzATACFIAJgADCJUAI-GAUsNcfgNHh8LFSKRNhYANZyBQpaKoOCQELAFpYIp8TYhCCkVjhW6suAwCBEuCk0UUbQwFLS1lQYACEoKvFwaGlfTqhFwABeMhcahSVmGInJd0ePheb0ZQlWnKoaCyNPpvzgkNQ-WYIipbuYdIIBQ9xVK5UqDmA_lAAlYUHanRgABYAOJgY5nJT-ABWYAEIrgkmAthgVBENBVJTwD1-AD5PfgADziKTvAHkH4IBBFktlnBwSuq-AaDR1vVN-3kd4FLs-rQOccTqftz5zjv1f20wNTrQ-rtb-nB5gL8eoJsOVuScfWpBqSCwOCuWKsUjwCL3euN89MNgcbBnqyTb8EIq4UOunz1NCsJjnq54qOodasK8rBgA-4S2HAAASACiMgAMJwKACieoegZEd8IRUBAkiYPcF4ITAgGipO8gOk6LrUtudJwayxallQXY4tiGi8agQ4lEJ2IiWJM7MD8YZlBUVTaAkXxxGAFD1B0IBdBpWlRmx5AOJWzB6eAFDDP4pmGLxi4-KK8FqExABSPA4amDHOcxQFTo6ZacQGPGOXxfaCQgwmiSF4nkFWMBSTJ0VyQpJRKZG0axvGia6QASgIFCDFhaCbLm-a2SF9m8U2jF1vhqQ5QQOh8AkpGutxFHvNRtH0Q4NVVX5HFtfSsn8WWCVRdFEnxRF0kTSF-6KRGVSqFY9hWLSITaFYqlaeKUAKFY8hhG4tjNHwNh6LY_ghKM_jkKwVjMJwMD7aQZr-HEfD6lgfCSNpnRTt0qZ6JIZZNEIDgADI5Q4tJQBQxBTJsmzMFQUwAKzHP4YDouVjn2SxDggeQgEXr-7DPTe3hAA&modules=true


[exif_bug_example]: https://react-pdf-repl.vercel.app/?cp_code=JYWwDg9gTgLgBAbzgEQgYwK4gKYDsYA0cACgIYDm2RAasNgO5ECSIFVcAyjAJ4A22HABbZs8AL5wAZlAgg4AIgACUbKTQwAtGAAmkgPQrc27CqjyA3AChLaCLgDO8R32z24AXk49-QkTAB0aCqkMNgAFAiWcHAARhDa3ABciHBgpNrawLjkyQCMAAxwYgRRcKBsyUj0wNowgnn5-UQQMQBW2OoAYsAwyfK2-KRZ8kUlYgCUVpbYAB6QsHDGkqQYvPBh4x4AfHBhpQA8qJg4-Ful0ftklHDO_O4It67-cQkS9sAAXtju8gCCAKzyM7REFwfa0BjnUE3bzfBCRaHQyT8GbIYAqdTAOx9GT0eQlRGg5GzADqUFIYD69HJYHxUMR5ApDQJhOiwmA5EEvQUBXyAFI6azoqReBzcABhOyhfB9NB4UJmFms1oYRzASTcSX4eWy-UmQWEsRielwYGE_YsNgm0GPe6Pez-cqUY1Cm5QNA_LkwMD2RJ6Aykej-cg9QQYGKqkwDaUBWwgAwdDBQewmPSzdUaaB0QYwLG4DSzUjgfj2PSsRypgAypCM9jQFOwAH18v5WmByPJrXA9GbERbWJQu9FbQ9YQ6ndgXUL7O7PTBvb7_eSgyG6uHI-6pfLArIE5hk6n05JM1BszAQnmCzMi2AS2XSBWoHpq7X62Am7lW-3O6ye13-1arojvajoDpOQ5uh68hej6foBiuobrimm7avgO7xhiSbIWmMwZlm8oXnYV43ne5YKs-NbaHWDaNgATF-HZdn-rIAYOQGwnaY6gWwU6sjOUEwYu8HBohEbIdG25xnuWGHrhx74Tml6FsWrj3o-FGvjRADMDE_oSzHmpabHThxo4uOOYG8YS_FzgucHLiJa5iVGW5oVJmEHk-R4nmehH5spt6qWRVaUdR76NgALLpTG9tCrHYBBwFcROVmIjZ0HzrBS6Bo5YbOShMbodJnk4Xhp4EbmREBaRD7kS-VFvk2_zRb-sWgvFiWmSBKWJbOGV2dlCFORuElubuHnYd5CnnpV_nXippbBU-9VhU2ABsLX6W1IIdexLiceZ3HOr1AmZUJDmrnlI2ubG42JiVU3lYpVXzYFi21SFmnhQA7JtiIGX2RkJXtdxmSWR3gUBfWCfZOWXUhLmobdGH3ZNck-RVSmvTV6krY1jYABx_dCAM7XoEL0LF-x6Fc2BmtTRxYPKZyTJYQA&modules=true