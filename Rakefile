rule "name-database/firstnames.csv" => "name-database/0717-182/nam_dict.txt" do
   File.open("name-database/firstnames.csv", 'w') do |out|
      out.write <<-HEAD
# List of first names, genders and country-specific frequencies
# This file is subject to the GNU Free Documentation License.
# Permission is granted to copy, distribute and/or modify
# this document under the terms of the GNU Free Documentation
# License, Version 1.2 or any later version published by the
# Free Software Foundation; with no Invariant Sections,
# no Front-Cover Texts, and no Back-Cover Texts.
#
# Copyright (c):
# 2007-2008:  Jörg MICHAEL, Adalbert-Stifter-Str. 11,
#             30655 Hannover, Germany
# Updated 2016:
#             Matthias Winkelmann, <m@matthi.coffee>
#             https://matthi.coffee
#             https://twitter.com/whereismatthi
#             Github: https://github.com/MatthiasWinkelmann/name-database
#
# Original work at http://www.heise.de/ct/ftp/07/17/182/
#
#
# This file is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty
# of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
#
# A copy of the license can be found in the file GNU_DOC.TXT.
# You should have received a copy of the GNU Free Documentation
# License along with this file;
# if not, write to the  Free Software Foundation, Inc.,
# 675 Mass Ave, Cambridge, MA 02139, USA.
#
# Gender is encoded in column 2 as:
#
# F  female
# 1F female if first part of name, otherwise mostly male
# ?F mostly female
# M  male
# 1M male if first part of name, otherwise mostly female
# ?M mostly male
# ?  unisex
#
# Frequencies are encoded in (2^x)% of the population,
# i. e. a "-2" in column 31 indicates a frequency between 2^-4 = 0.0625% and 2^-3 = 0.125% of the population of Great Britain
name;gender;frequencies
;;Great Britain;Ireland;U.S.A.;Italy;Malta;Portugal;Spain;France;Belgium;Luxembourg;the Netherlands;East Frisia;Germany;Austria;Swiss;Iceland;Denmark;Norway;Sweden;Finland;Estonia;Latvia;Lithuania;Poland;Czech Republic;Slovakia;Hungary;Romania;Bulgaria;Bosnia and Herzegovina;Croatia;Kosovo;Macedonia;Montenegro;Serbia;Slovenia;Albania;Greece;Russia;Belarus;Moldova;Ukraine;Armenia;Azerbaijan;Georgia;Kazakhstan/Uzbekistan,etc.;Turkey;Arabia/Persia;Israel;China;India/Sri Lanka;Japan;Korea;Vietnam;other countries
HEAD

      characters = {'<A/>' => ([256].pack("U*")),
      '<a/>' => ([257].pack("U*")),
      '<Â>' => ([258].pack("U*")),
      '<â>' => ([259].pack("U*")),
      '<A,>' => ([260].pack("U*")),
      '<a,>' => ([261].pack("U*")),
      '<C´>' => ([262].pack("U*")),
      '<c´>' => ([263].pack("U*")),
      '<C^>' => ([268].pack("U*")),
      '<CH>' => ([268].pack("U*")),
      '<c^>' => ([269].pack("U*")),
      '<c^>' => ([269].pack("U*")),
      '<d´>' => ([271].pack("U*")),
      '<DJ>' => ([272].pack("U*")),
      '<Ð>' => ([272].pack("U*")),
      '<ð>' => ([273].pack("U*")),
      '<dj>' => ([273].pack("U*")),
      '<E/>' => ([274].pack("U*")),
      '<e/>' => ([275].pack("U*")),
      '<E°>' => ([278].pack("U*")),
      '<e°>' => ([279].pack("U*")),
      '<E,>' => ([280].pack("U*")),
      '<e,>' => ([281].pack("U*")),
      '<Ê>' => ([282].pack("U*")),
      '<ê>' => ([283].pack("U*")),
      '<G^>' => ([286].pack("U*")),
      '<g^>' => ([287].pack("U*")),
      '<G,>' => ([290].pack("U*")),
      '<g´>' => ([291].pack("U*")),
      '<I/>' => ([298].pack("U*")),
      '<i/>' => ([299].pack("U*")),
      '<I°>' => ([304].pack("U*")),
      '<i>' => ([305].pack("U*")),
      '<IJ>' => ([306].pack("U*")),
      '<ij>' => ([307].pack("U*")),
      '<K,>' => ([310].pack("U*")),
      '<k,>' => ([311].pack("U*")),
      '<L,>' => ([315].pack("U*")),
      '<l,>' => ([316].pack("U*")),
      '<L´>' => ([317].pack("U*")),
      '<l´>' => ([318].pack("U*")),
      '<L/>' => ([321].pack("U*")),
      '<l/>' => ([322].pack("U*")),
      '<N,>' => ([325].pack("U*")),
      '<n,>' => ([326].pack("U*")),
      '<N^>' => ([327].pack("U*")),
      '<n^>' => ([328].pack("U*")),
      '<Ö>' => ([336].pack("U*")),
      '<ö>' => ([337].pack("U*")),
      'Œ' => ([338].pack("U*")),
      '<OE>' => ([338].pack("U*")),
      'œ' => ([339].pack("U*")),
      '<oe>' => ([339].pack("U*")),
      '<R^>' => ([344].pack("U*")),
      '<r^>' => ([345].pack("U*")),
      '<S,>' => ([350].pack("U*")),
      '<s,>' => ([351].pack("U*")),
      'Š' => ([352].pack("U*")),
      '<S^>' => ([352].pack("U*")),
      '<SH>' => ([352].pack("U*")),
      '<SCH>' => ([352].pack("U*")),
      '<sh>' => ([353].pack("U*")),
      'š' => ([353].pack("U*")),
      '<s^>' => ([353].pack("U*")),
      '<sch>' => ([353].pack("U*")),
      '<T,>' => ([354].pack("U*")),
      '<t,>' => ([355].pack("U*")),
      '<t´>' => ([357].pack("U*")),
      '<U/>' => ([362].pack("U*")),
      '<u/>' => ([363].pack("U*")),
      '<U°>' => ([366].pack("U*")),
      '<u°>' => ([367].pack("U*")),
      '<U,>' => ([370].pack("U*")),
      '<u,>' => ([371].pack("U*")),
      '<Z°>' => ([379].pack("U*")),
      '<z°>' => ([380].pack("U*")),
      '<Z^>' => ([381].pack("U*")),
      '<z^>' => ([382].pack("U*")),
      '<ß>' => ([3783].pack("U*"))}
      frequencies = {'1' => -8, '2' => -7, '3' => -6, '4' => -5, '5' => -4, '6' => -3, '7' => -2, '8' => -1, '9' => 0, 'A' => 1, 'B' => 2, 'C' => 4, 'D' => 5}
      File.open("name-database/0717-182/nam_dict.txt", 'r:iso-8859-1:utf-8').each do |line|
         puts line
         next if line[0] == '#'
         next if line[0] == '='
         next if line[29] == '+'
         gender = line.split(' ').first
         name = line.split(' ')[1].gsub(/<.+>/, characters)

         countries = line[30,55].split('').map { |freq|
            freq.empty? ? '' : frequencies[freq]
         }
         .join(';')
         newline = [name, gender, countries].join(';') + "\n"
         out.write(newline)
         puts newline
      end
   end
end
