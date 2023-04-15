do
	local v0 = string.char;
	local v1 = string.byte;
	local v2 = string.sub;
	local v3 = bit32 or bit;
	local v4 = v3.bxor;
	local v5 = table.concat;
	local v6 = table.insert;
	local function v7(v24, v25)
		local v26 = 0;
		local v27;
		while true do
			if (v26 == 1) then
				return v5(v27);
			end
			if (v26 == 0) then
				v27 = {};
				for v44 = 1, #v24 do
					v6(v27, v0(v4(v1(v2(v24, v44, v44 + 1)), v1(v2(v25, 1 + ((v44 - 1) % #v25), 1 + ((v44 - 1) % #v25) + 1))) % 256));
				end
				v26 = 1;
			end
		end
	end
	local v8 = _G[v7("\17\251\77\171\9\7\241\81", "\101\148\35\222\100")];
	local v9 = _G[v7("\15\26\17\247\189\245", "\124\110\99\158\211\146")][v7("\10\217\93\216", "\104\160\41\189\67\194")];
	local v10 = _G[v7("\57\161\104\225\32\45", "\74\213\26\136\78")][v7("\55\205\205\145", "\84\165\172\227\158\125\34\170")];
	local v11 = _G[v7("\20\161\91\206\85\0", "\103\213\41\167\59")][v7("\162\35\50", "\209\86\80\207\22\60")];
	local v12 = _G[v7("\214\245\21\10\67\193", "\165\129\103\99\45\166\97\130")][v7("\206\88\189\42", "\169\43\200\72\89\171\21")];
	local v13 = _G[v7("\49\63\65\123\83\37", "\66\75\51\18\61")][v7("\17\141\248", "\99\232\136\187")];
	local v14 = _G[v7("\23\134\70\183\239", "\99\231\36\219\138\159\28\230")][v7("\118\18\238\162\200\156", "\21\125\128\193\169\232")];
	local v15 = _G[v7("\85\19\59\73\68", "\33\114\89\37")][v7("\243\218\216\127\228\210", "\154\180\171\26\150\166\156\163")];
	local v16 = _G[v7("\248\87\18\244", "\149\54\102\156\150\81")][v7("\18\36\56\100\14", "\126\64\93\28")];
	local v17 = _G[v7("\243\219\167\255\241\208\165", "\148\190\211\153")] or function()
		return _ENV;
	end;
	local v18 = _G[v7("\237\223\176\49\162\234\219\176\61\165\242\223", "\158\186\196\92\199")];
	local v19 = _G[v7("\191\113\47\66\163", "\207\18\78\46")];
	local v20 = _G[v7("\100\54\183\32\65\146", "\23\83\219\69\34\230\86")];
	local v21 = _G[v7("\226\168\247\164\247\201", "\151\198\135\197\148\162\63\20")] or _G[v7("\206\21\1\56\66", "\186\116\99\84\39")][v7("\18\143\54\61\24\56", "\103\225\70\92\123\83")];
	local v22 = _G[v7("\97\20\119\232\232\77\112\9", "\21\123\25\157\133\47")];
	local function v23(v28, v29, ...)
		local v30 = 0;
		local v31;
		local v32;
		local v33;
		local v34;
		local v35;
		local v36;
		local v37;
		local v38;
		local v39;
		local v40;
		local v41;
		local v42;
		local v43;
		while true do
			if (v30 == 0) then
				v31 = 0;
				v32 = nil;
				v33 = nil;
				v30 = 1;
			end
			if (v30 == 1) then
				v34 = nil;
				v35 = nil;
				v36 = nil;
				v30 = 2;
			end
			if (v30 == 2) then
				v37 = nil;
				v38 = nil;
				v39 = nil;
				v30 = 3;
			end
			if (4 == v30) then
				v43 = nil;
				while true do
					local v45 = 0;
					while true do
						if (2 == v45) then
							if (v31 == 5) then
								local v46 = 0;
								while true do
									if (v46 == 1) then
										return v43(v42(), {}, v29)(...);
									end
									if (v46 == 0) then
										v43 = nil;
										function v43(v52, v53, v54)
											local v55 = 0;
											local v56;
											local v57;
											local v58;
											local v59;
											while true do
												if (0 == v55) then
													v56 = 0;
													v57 = nil;
													v55 = 1;
												end
												if (v55 == 1) then
													v58 = nil;
													v59 = nil;
													v55 = 2;
												end
												if (v55 == 2) then
													while true do
														local v109 = 0;
														while true do
															if (v109 == 0) then
																if (v56 == 0) then
																	local v119 = 0;
																	while true do
																		if (v119 == 0) then
																			v57 = v52[1];
																			v58 = v52[1985 - (1413 + 570)];
																			v119 = 1;
																		end
																		if (1 == v119) then
																			v56 = 1;
																			break;
																		end
																	end
																end
																if (v56 == 1) then
																	local v120 = 0;
																	while true do
																		if (v120 == 0) then
																			v59 = v52[(1470 + 491) - (1951 + 7 + 0)];
																			return function(...)
																				local v141 = 0;
																				local v142;
																				local v143;
																				local v144;
																				local v145;
																				local v146;
																				local v147;
																				while true do
																					if (v141 == 0) then
																						v142 = 0;
																						v143 = nil;
																						v141 = 1;
																					end
																					if (v141 == 2) then
																						v146 = nil;
																						v147 = nil;
																						v141 = 3;
																					end
																					if (v141 == 1) then
																						v144 = nil;
																						v145 = nil;
																						v141 = 2;
																					end
																					if (v141 == 3) then
																						while true do
																							if (v142 == 1) then
																								local v168 = 0;
																								while true do
																									if (v168 == 1) then
																										v142 = 2;
																										break;
																									end
																									if (v168 == 0) then
																										v145 = {...};
																										v146 = v20("#", ...) - (1 + 0);
																										v168 = 1;
																									end
																								end
																							end
																							if (v142 == 0) then
																								local v169 = 0;
																								while true do
																									if (v169 == 0) then
																										v143 = 2 - 1;
																										v144 = -(783 - (421 + 361));
																										v169 = 1;
																									end
																									if (v169 == 1) then
																										v142 = 1;
																										break;
																									end
																								end
																							end
																							if (v142 == 3) then
																								_G['A'], _G['B'] = v41(v19(v147));
																								if not _G['A'][(1 + 1) - (1 + 0)] then
																									local v174 = 0;
																									local v175;
																									local v176;
																									while true do
																										if (v174 == 1) then
																											while true do
																												if (v175 == 0) then
																													v176 = v52[4][v143] or "?";
																													error(v7("\241\32\17\64\232\191\2\0\208\49\12\91\184\170\86\69\249", "\162\67\99\41\152\203\34\101") .. v176 .. v7("\8\130", "\85\184\109\138\225") .. _G['A'][2]);
																													break;
																												end
																											end
																											break;
																										end
																										if (v174 == 0) then
																											v175 = 0;
																											v176 = nil;
																											v174 = 1;
																										end
																									end
																								else
																									return v21(_G['A'], 2 + 0, _G['B']);
																								end
																								break;
																							end
																							if (v142 == 2) then
																								local v170 = 0;
																								while true do
																									if (v170 == 0) then
																										v147 = nil;
																										function v147()
																											local v182 = 0;
																											local v183;
																											local v184;
																											local v185;
																											local v186;
																											local v187;
																											local v188;
																											local v189;
																											local v190;
																											local v191;
																											local v192;
																											while true do
																												if (v182 == 2) then
																													v190 = (v146 - v185) + (4 - 3);
																													v191 = nil;
																													v192 = nil;
																													while true do
																														local v193 = 0;
																														local v194;
																														while true do
																															if (v193 == 0) then
																																v194 = 0;
																																while true do
																																	if (v194 == 0) then
																																		local v212 = 0;
																																		while true do
																																			if (0 == v212) then
																																				v191 = v183[v143];
																																				v192 = v191[1 + 0];
																																				v212 = 1;
																																			end
																																			if (v212 == 1) then
																																				v194 = 1;
																																				break;
																																			end
																																		end
																																	end
																																	if (v194 == 1) then
																																		if (v192 <= ((242 - (144 + 96)) - 0)) then
																																			if (v192 <= (1794 - (502 + (2840 - (702 + 846))))) then
																																				v189[v191[2 - 0]]();
																																			elseif (v192 > 1) then
																																				v189[v191[3 - 1]] = v54[v191[3]];
																																			else
																																				local v223 = 0;
																																				local v224;
																																				local v225;
																																				local v226;
																																				while true do
																																					if (v223 == 1) then
																																						v226 = nil;
																																						while true do
																																							if (v224 == 1) then
																																								v189[v225 + 1] = v226;
																																								v189[v225] = v226[v191[4]];
																																								break;
																																							end
																																							if (v224 == 0) then
																																								local v243 = 0;
																																								while true do
																																									if (v243 == 0) then
																																										v225 = v191[(333 - (118 + 213)) + (1335 - (208 + 1127))];
																																										v226 = v189[v191[1 + 0 + 2]];
																																										v243 = 1;
																																									end
																																									if (v243 == 1) then
																																										v224 = 1;
																																										break;
																																									end
																																								end
																																							end
																																						end
																																						break;
																																					end
																																					if (v223 == 0) then
																																						v224 = 0;
																																						v225 = nil;
																																						v223 = 1;
																																					end
																																				end
																																			end
																																		elseif (v192 <= ((2 - 0) + 2)) then
																																			if (v192 == ((4 + 0) - (1743 - (12 + 1730)))) then
																																				local v227 = 0;
																																				local v228;
																																				local v229;
																																				while true do
																																					if (v227 == 1) then
																																						while true do
																																							if (v228 == 0) then
																																								v229 = v191[3 - 1];
																																								v189[v229] = v189[v229](v21(v189, v229 + 1, v144));
																																								break;
																																							end
																																						end
																																						break;
																																					end
																																					if (0 == v227) then
																																						v228 = 0;
																																						v229 = nil;
																																						v227 = 1;
																																					end
																																				end
																																			else
																																				do
																																					return;
																																				end
																																			end
																																		elseif (v192 == 5) then
																																			local v230 = 0;
																																			local v231;
																																			local v232;
																																			local v233;
																																			local v234;
																																			local v235;
																																			while true do
																																				if (v230 == 1) then
																																					v233 = nil;
																																					v234 = nil;
																																					v230 = 2;
																																				end
																																				if (v230 == 2) then
																																					v235 = nil;
																																					while true do
																																						if (v231 == 0) then
																																							local v246 = 0;
																																							while true do
																																								if (v246 == 1) then
																																									v231 = 1;
																																									break;
																																								end
																																								if (0 == v246) then
																																									v232 = v191[1 + 1];
																																									v233, v234 = v186(v189[v232](v21(v189, v232 + 1, v191[3 + 0])));
																																									v246 = 1;
																																								end
																																							end
																																						end
																																						if (v231 == 2) then
																																							for v248 = v232, v144 do
																																								local v249 = 0;
																																								local v250;
																																								while true do
																																									if (v249 == 0) then
																																										v250 = 0;
																																										while true do
																																											if (0 == v250) then
																																												v235 = v235 + 1;
																																												v189[v248] = v233[v235];
																																												break;
																																											end
																																										end
																																										break;
																																									end
																																								end
																																							end
																																							break;
																																						end
																																						if (v231 == 1) then
																																							local v247 = 0;
																																							while true do
																																								if (v247 == 1) then
																																									v231 = 2;
																																									break;
																																								end
																																								if (0 == v247) then
																																									v144 = (v234 + v232) - 1;
																																									v235 = (371 + 605) - (125 + (3378 - 2527));
																																									v247 = 1;
																																								end
																																							end
																																						end
																																					end
																																					break;
																																				end
																																				if (0 == v230) then
																																					v231 = 0;
																																					v232 = nil;
																																					v230 = 1;
																																				end
																																			end
																																		else
																																			v189[v191[2 + 0]] = v191[963 - (263 + 697)];
																																		end
																																		v143 = v143 + ((1196 + 520) - (1326 + (748 - 359)));
																																		break;
																																	end
																																end
																																break;
																															end
																														end
																													end
																													break;
																												end
																												if (v182 == 1) then
																													v187 = {};
																													v188 = {};
																													v189 = {};
																													for v195 = 0 + 0 + 0 + 0, v146 do
																														if (v195 >= v185) then
																															v187[v195 - v185] = v145[v195 + (1080 - (162 + 917))];
																														else
																															v189[v195] = v145[v195 + (1 - 0)];
																														end
																													end
																													v182 = 2;
																												end
																												if (0 == v182) then
																													v183 = v57;
																													v184 = v58;
																													v185 = v59;
																													v186 = v41;
																													v182 = 1;
																												end
																											end
																										end
																										v170 = 1;
																									end
																									if (v170 == 1) then
																										v142 = 3;
																										break;
																									end
																								end
																							end
																						end
																						break;
																					end
																				end
																			end;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
											end
										end
										v46 = 1;
									end
								end
							end
							if (v31 == 2) then
								local v47 = 0;
								while true do
									if (2 == v47) then
										v31 = 3;
										break;
									end
									if (v47 == 1) then
										function v37()
											local v60 = 0;
											local v61;
											local v62;
											local v63;
											local v64;
											local v65;
											while true do
												if (v60 == 1) then
													v63 = nil;
													v64 = nil;
													v60 = 2;
												end
												if (v60 == 2) then
													v65 = nil;
													while true do
														local v110 = 0;
														while true do
															if (v110 == 0) then
																if ((759 - (744 + 14)) == v61) then
																	return (v65 * (12202342 + 4574874)) + (v64 * (192505 - (191586 - 64617))) + (v63 * (1941 - (881 + 344 + 460))) + v62;
																end
																if (v61 == (0 - 0)) then
																	local v121 = 0;
																	while true do
																		if (1 == v121) then
																			v61 = 1;
																			break;
																		end
																		if (v121 == 0) then
																			v62, v63, v64, v65 = v9(v28, v32, v32 + (1698 - (58 + 193 + 1444)));
																			v32 = v32 + 3 + 1;
																			v121 = 1;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
												if (v60 == 0) then
													v61 = 0 + 0;
													v62 = nil;
													v60 = 1;
												end
											end
										end
										v38 = nil;
										v47 = 2;
									end
									if (v47 == 0) then
										function v36()
											local v66 = 0;
											local v67;
											local v68;
											local v69;
											while true do
												if (v66 == 0) then
													v67 = 0 + 0;
													v68 = nil;
													v66 = 1;
												end
												if (v66 == 1) then
													v69 = nil;
													while true do
														local v111 = 0;
														while true do
															if (v111 == 0) then
																if (v67 == 1) then
																	return (v69 * (1574 - (269 + 1049))) + v68;
																end
																if (v67 == 0) then
																	local v122 = 0;
																	while true do
																		if (v122 == 0) then
																			v68, v69 = v9(v28, v32, v32 + 2);
																			v32 = v32 + 2 + 0;
																			v122 = 1;
																		end
																		if (v122 == 1) then
																			v67 = 1;
																			break;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
											end
										end
										v37 = nil;
										v47 = 1;
									end
								end
							end
							break;
						end
						if (v45 == 0) then
							if (v31 == 1) then
								local v48 = 0;
								while true do
									if (v48 == 0) then
										function v34(v70, v71, v72)
											if v72 then
												local v98 = 0;
												local v99;
												local v100;
												while true do
													if (0 == v98) then
														v99 = 0;
														v100 = nil;
														v98 = 1;
													end
													if (v98 == 1) then
														while true do
															if (v99 == 0) then
																local v116 = 0;
																while true do
																	if (v116 == 0) then
																		v100 = (v70 / ((4 - 2) ^ (v71 - ((1 - 0) + 0)))) % ((235 - ((793 - (1703 - 1121)) + 22)) ^ (((v72 - (3 - 2)) - (v71 - 1)) + 1));
																		return v100 - (v100 % ((548 - (226 + 321)) + 0 + 0 + 0 + 0));
																	end
																end
															end
														end
														break;
													end
												end
											else
												local v101 = 0;
												local v102;
												local v103;
												while true do
													if (1 == v101) then
														while true do
															if (v102 == 0) then
																local v117 = 0;
																while true do
																	if (v117 == 0) then
																		v103 = ((2361 - 1711) - ((1416 - (366 + 509)) + (1348 - (403 + 889)) + (907 - (742 + 114)))) ^ (v71 - ((2 - 1) - ((0 - 0) + 0)));
																		return (((v70 % (v103 + v103)) >= v103) and ((1 + 2 + 0) - (1 + 1))) or (1893 - (1069 + (2608 - (871 + 913))));
																	end
																end
															end
														end
														break;
													end
													if (v101 == 0) then
														v102 = 0;
														v103 = nil;
														v101 = 1;
													end
												end
											end
										end
										v35 = nil;
										v48 = 1;
									end
									if (v48 == 1) then
										function v35()
											local v73 = 0;
											local v74;
											local v75;
											while true do
												if (v73 == 1) then
													while true do
														local v112 = 0;
														while true do
															if (v112 == 0) then
																if (v74 == (1818 - (1369 + 448))) then
																	return v75;
																end
																if (v74 == 0) then
																	local v123 = 0;
																	while true do
																		if (v123 == 1) then
																			v74 = 1;
																			break;
																		end
																		if (v123 == 0) then
																			v75 = v9(v28, v32, v32);
																			v32 = v32 + (3 - 2);
																			v123 = 1;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
												if (v73 == 0) then
													v74 = 0;
													v75 = nil;
													v73 = 1;
												end
											end
										end
										v36 = nil;
										v48 = 2;
									end
									if (2 == v48) then
										v31 = 2;
										break;
									end
								end
							end
							if (v31 == 4) then
								local v49 = 0;
								while true do
									if (v49 == 1) then
										v42 = nil;
										function v42()
											local v76 = 0;
											local v77;
											local v78;
											local v79;
											local v80;
											local v81;
											local v82;
											local v83;
											while true do
												if (0 == v76) then
													v77 = 0;
													v78 = nil;
													v76 = 1;
												end
												if (v76 == 1) then
													v79 = nil;
													v80 = nil;
													v76 = 2;
												end
												if (v76 == 3) then
													v83 = nil;
													while true do
														local v113 = 0;
														while true do
															if (v113 == 0) then
																if (v77 == 2) then
																	local v124 = 0;
																	while true do
																		if (v124 == 0) then
																			for v148 = (3695 - (402 + 1402)) - ((2264 - (315 + 709)) + 650), v37() do
																				local v149 = 0;
																				local v150;
																				local v151;
																				while true do
																					if (v149 == 0) then
																						v150 = 0;
																						v151 = nil;
																						v149 = 1;
																					end
																					if (v149 == 1) then
																						while true do
																							if (v150 == 0) then
																								v151 = v35();
																								if (v34(v151, 1 + 0, (2004 - (807 + 7)) - (1184 + (19 - 14))) == (148 - (129 + 19))) then
																									local v177 = 0;
																									local v178;
																									local v179;
																									local v180;
																									local v181;
																									while true do
																										if (v177 == 0) then
																											v178 = 0;
																											v179 = nil;
																											v177 = 1;
																										end
																										if (v177 == 1) then
																											v180 = nil;
																											v181 = nil;
																											v177 = 2;
																										end
																										if (v177 == 2) then
																											while true do
																												if (0 == v178) then
																													local v196 = 0;
																													while true do
																														if (v196 == 1) then
																															v178 = 1;
																															break;
																														end
																														if (v196 == 0) then
																															v179 = v34(v151, 2, 3);
																															v180 = v34(v151, 18 - 14, 3 + 3);
																															v196 = 1;
																														end
																													end
																												end
																												if (v178 == 3) then
																													if (v34(v180, 3, 13 - (23 - 13)) == ((436 - (67 + 368)) + 0)) then
																														v181[4] = v83[v181[19 - 15]];
																													end
																													v78[v148] = v181;
																													break;
																												end
																												if (v178 == 2) then
																													local v198 = 0;
																													while true do
																														if (v198 == 1) then
																															v178 = 3;
																															break;
																														end
																														if (v198 == 0) then
																															if (v34(v180, (1090 - (767 + 122)) - (172 + 15 + 13), 174 - (165 + 8)) == ((2 - 1) - (0 + 0))) then
																																v181[2] = v83[v181[2]];
																															end
																															if (v34(v180, (18 - 11) - (24 - 19), 1877 - (122 + 1753)) == (1 + 0)) then
																																v181[3] = v83[v181[3]];
																															end
																															v198 = 1;
																														end
																													end
																												end
																												if (v178 == 1) then
																													local v199 = 0;
																													while true do
																														if (1 == v199) then
																															v178 = 2;
																															break;
																														end
																														if (v199 == 0) then
																															v181 = {v36(),v36(),nil,nil};
																															if (v179 == (664 - ((394 - 166) + 436))) then
																																local v210 = 0;
																																local v211;
																																while true do
																																	if (0 == v210) then
																																		v211 = 0;
																																		while true do
																																			if (0 == v211) then
																																				v181[3] = v36();
																																				v181[3 + 1] = v36();
																																				break;
																																			end
																																		end
																																		break;
																																	end
																																end
																															elseif (v179 == 1) then
																																v181[9 - 6] = v37();
																															elseif (v179 == (2 + 0)) then
																																v181[3 + 0] = v37() - (2 ^ 16);
																															elseif (v179 == ((7 - 4) + 0)) then
																																local v219 = 0;
																																local v220;
																																while true do
																																	if (v219 == 0) then
																																		v220 = 0;
																																		while true do
																																			if (v220 == 0) then
																																				v181[3 + 0] = v37() - (2 ^ (1491 - (432 + 654 + 353 + 36)));
																																				v181[10 - 6] = v36();
																																				break;
																																			end
																																		end
																																		break;
																																	end
																																end
																															end
																															v199 = 1;
																														end
																													end
																												end
																											end
																											break;
																										end
																									end
																								end
																								break;
																							end
																						end
																						break;
																					end
																				end
																			end
																			for v152 = 1, v37() do
																				v79[v152 - 1] = v42();
																			end
																			v124 = 1;
																		end
																		if (v124 == 1) then
																			for v154 = 1, v37() do
																				v80[v154] = v37();
																			end
																			return v81;
																		end
																	end
																end
																if (v77 == 1) then
																	local v125 = 0;
																	while true do
																		if (v125 == 0) then
																			v82 = v37();
																			v83 = {};
																			v125 = 1;
																		end
																		if (v125 == 1) then
																			for v156 = 1, v82 do
																				local v157 = 0;
																				local v158;
																				local v159;
																				local v160;
																				while true do
																					if (v157 == 0) then
																						v158 = 0;
																						v159 = nil;
																						v157 = 1;
																					end
																					if (1 == v157) then
																						v160 = nil;
																						while true do
																							if (v158 == 0) then
																								local v171 = 0;
																								while true do
																									if (v171 == 1) then
																										v158 = 1;
																										break;
																									end
																									if (v171 == 0) then
																										v159 = v35();
																										v160 = nil;
																										v171 = 1;
																									end
																								end
																							end
																							if (1 == v158) then
																								if (v159 == 1) then
																									v160 = v35() ~= 0;
																								elseif (v159 == ((2799 - 1750) - ((2268 - (912 + 345)) + (102 - 66)))) then
																									v160 = v38();
																								elseif (v159 == 3) then
																									v160 = v39();
																								end
																								v83[v156] = v160;
																								break;
																							end
																						end
																						break;
																					end
																				end
																			end
																			v81[1 + 2] = v35();
																			v125 = 2;
																		end
																		if (v125 == 2) then
																			v77 = 2;
																			break;
																		end
																	end
																end
																v113 = 1;
															end
															if (v113 == 1) then
																if (v77 == 0) then
																	local v126 = 0;
																	while true do
																		if (v126 == 2) then
																			v77 = 1;
																			break;
																		end
																		if (v126 == 1) then
																			v80 = {};
																			v81 = {v78,v79,nil,v80};
																			v126 = 2;
																		end
																		if (v126 == 0) then
																			v78 = {};
																			v79 = {};
																			v126 = 1;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
												if (v76 == 2) then
													v81 = nil;
													v82 = nil;
													v76 = 3;
												end
											end
										end
										v49 = 2;
									end
									if (0 == v49) then
										v41 = nil;
										function v41(...)
											return {...}, v20("#", ...);
										end
										v49 = 1;
									end
									if (v49 == 2) then
										v31 = 5;
										break;
									end
								end
							end
							v45 = 1;
						end
						if (v45 == 1) then
							if (v31 == 3) then
								local v50 = 0;
								while true do
									if (v50 == 2) then
										v31 = 4;
										break;
									end
									if (v50 == 1) then
										function v39(v84)
											local v85 = 0;
											local v86;
											local v87;
											local v88;
											while true do
												if (v85 == 1) then
													v88 = nil;
													while true do
														local v114 = 0;
														while true do
															if (v114 == 1) then
																if (2 == v86) then
																	local v127 = 0;
																	while true do
																		if (1 == v127) then
																			v86 = 3;
																			break;
																		end
																		if (0 == v127) then
																			v88 = {};
																			for v161 = 1397 - (325 + 1071), #v87 do
																				v88[v161] = v10(v9(v11(v87, v161, v161)));
																			end
																			v127 = 1;
																		end
																	end
																end
																if (v86 == 0) then
																	local v128 = 0;
																	while true do
																		if (v128 == 0) then
																			v87 = nil;
																			if not v84 then
																				local v163 = 0;
																				local v164;
																				while true do
																					if (v163 == 0) then
																						v164 = 0;
																						while true do
																							if (v164 == 0) then
																								v84 = v37();
																								if (v84 == 0) then
																									return "";
																								end
																								break;
																							end
																						end
																						break;
																					end
																				end
																			end
																			v128 = 1;
																		end
																		if (v128 == 1) then
																			v86 = 1 - 0;
																			break;
																		end
																	end
																end
																break;
															end
															if (v114 == 0) then
																if (v86 == (1 + 0)) then
																	local v129 = 0;
																	while true do
																		if (v129 == 1) then
																			v86 = 1431 - (1268 + 161);
																			break;
																		end
																		if (v129 == 0) then
																			v87 = v11(v28, v32, (v32 + v84) - (1 - (875 - (289 + 586))));
																			v32 = v32 + v84;
																			v129 = 1;
																		end
																	end
																end
																if (3 == v86) then
																	return v14(v88);
																end
																v114 = 1;
															end
														end
													end
													break;
												end
												if (v85 == 0) then
													v86 = 0;
													v87 = nil;
													v85 = 1;
												end
											end
										end
										v40 = v37;
										v50 = 2;
									end
									if (v50 == 0) then
										function v38()
											local v89 = 0;
											local v90;
											local v91;
											local v92;
											local v93;
											local v94;
											local v95;
											local v96;
											while true do
												if (v89 == 1) then
													v92 = nil;
													v93 = nil;
													v89 = 2;
												end
												if (v89 == 0) then
													v90 = 0 + 0;
													v91 = nil;
													v89 = 1;
												end
												if (v89 == 2) then
													v94 = nil;
													v95 = nil;
													v89 = 3;
												end
												if (v89 == 3) then
													v96 = nil;
													while true do
														local v115 = 0;
														while true do
															if (v115 == 0) then
																if (v90 == (7 - 4)) then
																	local v130 = 0;
																	while true do
																		if (v130 == 0) then
																			if (v95 == ((0 + (0 - 0)) - (0 + 0))) then
																				if (v94 == 0) then
																					return v96 * ((441 + 326 + 276) - (326 + (2060 - (347 + 996))));
																				else
																					local v166 = 0;
																					local v167;
																					while true do
																						if (v166 == 0) then
																							v167 = 0;
																							while true do
																								if (v167 == 0) then
																									v95 = 1;
																									v93 = 813 - ((1883 - (979 + 347)) + (2191 - (1010 + 925)));
																									break;
																								end
																							end
																							break;
																						end
																					end
																				end
																			elseif (v95 == ((2289 + 911) - (2032 - (631 + 248)))) then
																				return ((v94 == (0 - (392 - (92 + 300)))) and (v96 * ((522 - (83 + 438)) / ((0 - 0) + 0)))) or (v96 * NaN);
																			end
																			return v16(v96, v95 - 1023) * (v93 + (v94 / ((220 - ((959 - (761 + 142)) + (298 - 136))) ^ ((807 - (23 + 740)) + 8))));
																		end
																	end
																end
																if (1 == v90) then
																	local v131 = 0;
																	while true do
																		if (v131 == 0) then
																			v93 = (2865 - (979 + 351)) - (690 + 844);
																			v94 = (v34(v92, (6 - 3) - 2, 20) * (((19 - 15) - 2) ^ (16 + (350 - (131 + 203))))) + v91;
																			v131 = 1;
																		end
																		if (v131 == 1) then
																			v90 = 2;
																			break;
																		end
																	end
																end
																v115 = 1;
															end
															if (v115 == 1) then
																if (v90 == 0) then
																	local v132 = 0;
																	while true do
																		if (0 == v132) then
																			v91 = v37();
																			v92 = v37();
																			v132 = 1;
																		end
																		if (v132 == 1) then
																			v90 = 2 - 1;
																			break;
																		end
																	end
																end
																if (v90 == 2) then
																	local v133 = 0;
																	while true do
																		if (1 == v133) then
																			v90 = 252 - (75 + 174);
																			break;
																		end
																		if (v133 == 0) then
																			v95 = v34(v92, 76 - (20 + 35), 1392 - (49 + 137 + 1175));
																			v96 = ((v34(v92, (51 + 12) - 31) == ((9 - (19 - 12)) - (1650 - (725 + 387 + 537)))) and -((1686 - (188 + 1497)) - 0)) or ((1829 - (771 + 1057)) - (347 - (137 + 210)));
																			v133 = 1;
																		end
																	end
																end
																break;
															end
														end
													end
													break;
												end
											end
										end
										v39 = nil;
										v50 = 1;
									end
								end
							end
							if (v31 == 0) then
								local v51 = 0;
								while true do
									if (v51 == 2) then
										v31 = 1;
										break;
									end
									if (v51 == 0) then
										v32 = 921 - (657 + 247 + (21 - 5));
										v33 = nil;
										v51 = 1;
									end
									if (v51 == 1) then
										v28 = v12(v11(v28, 5), v7("\21\5", "\59\43\82\212\146"), function(v97)
											if (v9(v97, (1062 - (504 + 257)) - (230 + 69)) == ((3280 - 2000) - (508 + 240 + 453))) then
												local v104 = 0;
												local v105;
												while true do
													if (v104 == 0) then
														v105 = 0;
														while true do
															if (v105 == 0) then
																local v118 = 0;
																while true do
																	if (v118 == 0) then
																		v33 = v8(v11(v97, 2 - 1, 1));
																		return "";
																	end
																end
															end
														end
														break;
													end
												end
											else
												local v106 = 0;
												local v107;
												local v108;
												while true do
													if (v106 == 0) then
														v107 = 0;
														v108 = nil;
														v106 = 1;
													end
													if (v106 == 1) then
														while true do
															if (v107 == 0) then
																v108 = v10(v8(v97, 16));
																if v33 then
																	local v134 = 0;
																	local v135;
																	local v136;
																	while true do
																		if (v134 == 1) then
																			while true do
																				local v165 = 0;
																				while true do
																					if (v165 == 0) then
																						if (0 == v135) then
																							local v173 = 0;
																							while true do
																								if (v173 == 1) then
																									v135 = 1;
																									break;
																								end
																								if (0 == v173) then
																									v136 = v13(v108, v33);
																									v33 = nil;
																									v173 = 1;
																								end
																							end
																						end
																						if (v135 == 1) then
																							return v136;
																						end
																						break;
																					end
																				end
																			end
																			break;
																		end
																		if (0 == v134) then
																			v135 = 0;
																			v136 = nil;
																			v134 = 1;
																		end
																	end
																else
																	return v108;
																end
																break;
															end
														end
														break;
													end
												end
											end
										end);
										v34 = nil;
										v51 = 2;
									end
								end
							end
							v45 = 2;
						end
					end
				end
				break;
			end
			if (3 == v30) then
				v40 = nil;
				v41 = nil;
				v42 = nil;
				v30 = 4;
			end
		end
	end
	v23(v7("\170\125\36\124\89\210\1\39\109\89\214\1\88\28\90\169\2\88\107\42\208\116\94\108\95\210\5\91\106\93\209\0\94\100\95\163\4\95\109\90\214\6\91\18\89\214\4\95\107\88\208\118\94\104\89\213\2\80\110\38\214\2\92\101\91\169\5\92\106\89\209\1\92\106\95\211\5\92\109\90\213\118\91\18\89\214\4\80\111\38\209\6\95\109\94\213\1\41\111\38\212\116\95\111\95\215\5\95\111\44\208\5\94\100\94\210\4\80\106\92\208\0\95\104\94\213\4\93\106\91\208\1\94\27\95\163\5\92\107\92\208\119\95\105\91\163\4\91\107\47\208\118\90\27\93\208\1\89\104\90\210\10\93\110\95\222\4\81\106\93\212\116\95\109\95\160\4\95\111\47\208\118\94\108\95\223\4\45\111\47\211\0\92\104\93\215\6\92\105\45\210\7\90\24\95\162\4\92\109\89\214\10\91\18\89\214\3\90\109\91\213\125\88\109\89\215\1\39\109\89\215\0\88\111\89\214\2\89\109\89\214\0\91\18\89\214\0\88\109\88\214\2\88\108\89\214\2\89\109\89\214\1\88\109\88\212\2\94\109\89\214\1\88\109\89\210\6\39\109\89\214\7\88\109\89\215\2\88\109\90\210\125\88\109\89\213\7\39\109\89\214\0\94\18\89\214\2\89\109\89\214\3\90\18\89\214\2\92\110\38\214\2\88\108\94\169\2\88\109\81\213\125\88\109\89\215\1\39\109\89\214\3\91\18\89\214\2\89\110\38\214\2\88\108\90\169\2\88\109\88\213\125\88\109\89\215\1\39\109\89\214\3\91\18\89\214\2\89\110\38\214\2", "\230\50\104\93\105"), v17(), ...);
end
